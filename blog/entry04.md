# Entry 4
##### 3/11/23

After some time with tinkering and deciding on the tool I want, I decided on Aframe.
I used the following code in JSBIN to make a stick figure.
```html
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position=".2 .7 -4" rotation="0 0 15" width=".3" height="1.5" color="#000000"></a-box>
      <a-box position="-.2 .7 -4" rotation="0 0 -15" width=".3" height="1.5" color="#000000"></a-box>
      <a-box position="-.6 3 -4" rotation="0 0 45" width=".3" height="1.5" color="#000000"></a-box>
      <a-box position=".6 3 -4" rotation="0 0 -45" width=".3" height="1.5" color="#000000"></a-box>
      <a-sphere position="0 3.5 -3.9" rotation="0 0 -45" radius=".5" color="#000000" ></a-sphere>
      <a-box position="0 2 -4" rotation="0 0 0" width=".3" height="1.5" color="#000000"></a-box>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC4A4"></a-plane>
      <a-sky color="#FCEFEF"></a-sky>
    </a-scene>
  </body>
</html>
```

![image](https://github.com/user-attachments/assets/d6613b9e-da19-4d16-98cd-8a485e60d061)

The code makes a pretty simple stick figure out of rectangles and an orb as a head, a pretty simple design, but I know more is possible with A-frame, which is why I settled on it. I started from the bottom up, making the legs out mirrored in a way they would touch when put together well enough, then I made the torso which was another box. Then I added the arms which were two more boxes with mirrored rotation and position. I learned all of this by myself by tinkering with original a-frame code.

## Skills
For this I worked on my problem solving and initiation skills.

### Problem Solving
For this assignment I improved my problem solving skills by figuring out how to use A-frame by myself, which was easier than I thought it would be, because of this I was able to complete this blog. 

### Initiation 
For this assigment, I originally struggled with beginning it as I struggle with assignments that I perceive to have massive scope and diffuculty. With this assignment I was able to realize I was more capable than I originally thought I was.

## Next Steps
Now that I have learnt A-Frame at a basic level, I plan to keep tinkering with my tool to learn how to use better, more and more, and create more complex models with this software in the future.

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
