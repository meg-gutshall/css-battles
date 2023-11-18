# Problem #175 - Evil Cat

## Attempt #1

Score: 600<br />
Characters: 1264

```html
<div class="ear left-ear"></div>
<div class="ear right-ear"></div>
<div class="head">
  <div class="eye left-eye">
    <div class="iris"></div>
  </div>
  <div class="eye right-eye">
    <div class="iris"></div>
  </div>
  <div class="nose"></div>
</div>
<style>
  * {
    background: var(--b, #ED6A9D);
  }
  body, div {
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
  }
  .ear {
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 0 40px 50px;
    border-color: transparent transparent #050044;
    top: 81px;
  }
  .left-ear {
    rotate: -145deg;
    left: 98px;
  }
  .right-ear {
    rotate: 145deg;
    right: 98px;
  }
  .head {
    width: 180px;
    height: 150px;
    border-radius: 50%;
    --b: #050044;
    top: 90px;
  }
  .eye {
    width: 40px;
    height: 40px;
    --b: #FFC100;
    border-radius: 50% 0;
    rotate: 45deg;
    top: 40px;
  }
  .left-eye {
    left: 35px;
  }
  .right-eye {
    right: 35px;
  }
  .iris {
    width: 10px;
    height: 30px;
    --b: #050044;
    border-radius: 50%;
    rotate: -45deg;
  }
  .nose {
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 15px 15px 0;
    border-color: #ED6A9D #050044 #050044;
    bottom: 40px;
  }
</style>
```

## Attempt #2

Score: 600.02<br />
Characters: 1047

```html
<div ear l></div>
<div ear r></div>
<div h>
  <div e ly>
    <div i></div>
  </div>
  <div e ry>
    <div i></div>
  </div>
  <div n></div>
</div>
<style>
  * {
    background: var(--b, #ED6A9D);
    border-radius: var(--r, 0%);
  }
  body, div {
    display: grid;
    place-items: center;
  }
  div {
    position: absolute;
  }
  [ear] {
    border-style: solid;
    border-width: 0 40 50;
    border-color: transparent transparent #050044;
    top: 81;
  }
  [l] {
    rotate: -145deg;
    left: 98;
  }
  [r] {
    rotate: 145deg;
    right: 98;
  }
  [h] {
    width: 180;
    height: 150;
    --b: #050044;
    --r: 50%;
    top: 90;
  }
  [e] {
    width: 40;
    height: 40;
    --b: #FFC100;
    --r: 50% 0;
    rotate: 45deg;
    top: 40;
  }
  [ly] {
    left: 35;
  }
  [ry] {
    right: 35;
  }
  [i] {
    width: 10;
    height: 30;
    --b: #050044;
    --r: 50%;
    rotate: -45deg;
  }
  [n] {
    border-style: solid;
    border-width: 15 15 0;
    border-color: #ED6A9D #050044 #050044;
    --r: 0;
    bottom: 40;
  }
</style>
```

## Attempt #3

Score: 600.62<br />
Characters: 678

```html
<div ear l></div><div ear r></div><div h><div e ly><div i></div></div><div e ry><div i></div></div><div n><style>*{background:var(--b,#ED6A9D);border-radius:var(--r,0%)}body,div{display:grid;place-items:center}div{position:absolute}[ear]{border-style:solid;border-width:0 40 50;border-color:transparent transparent#050044;top:81}[l]{rotate:-145deg;left:98}[r]{rotate:145deg;right:98}[h]{width:180;height:150;--b:#050044;--r:50%;top:90}[e]{width:40;height:40;--b:#FFC100;--r:50% 0;rotate:45deg;top:40}[ly]{left:35}[ry]{right:35}[i]{width:10;height:30;--b:#050044;--r:50%;rotate:-45deg}[n]{border-style:solid;border-width:15 15 0;border-color:#ED6A9D#050044#050044;--r:0;bottom:40
```
