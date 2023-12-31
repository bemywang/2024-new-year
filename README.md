# 2024-new-year🎆
[Click Here on GitHub Page](https://bemywang.github.io/2024-new-year/)

<img width="1137" alt="image" src="https://github.com/bemywang/2024-new-year/assets/84611026/d17e8f19-1658-4892-a474-50526151eff4">

<hr>
The UI was modified. In order to put content in the center of view. <br>
Please find the code in `index.html` <br>
Line 180, I have added:
```
<div class="center-content">
```

and  `style.css` <br>
Line 354-370, I have added 

```css
.center-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 1; /* Bring the content to the front */
  text-align: center;
  color: white; /* Set text color to white or your preference */
}
.center-content > h1 {
  font-size: 30px;
  margin-bottom: 20px;
}

.center-content > p {
  margin-bottom: 20px;
}
```
original code is from below:<br>
credits: Caleb Miller: A Pen created on CodePen.io. Original URL: [https://codepen.io/MillerTime/pen/XgpNwb](https://codepen.io/MillerTime/pen/XgpNwb).

