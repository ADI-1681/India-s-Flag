<html>
<head>
<title>INDIA'S FLAG</title>
<style>
body {
  height: 100vh;
  display: grid;
  place-items: center;
  background-color: aliceblue;
}

* {
  box-sizing: border-box;
  margin: 0;
}

:root {
  --saffron: #ff6600;
  --green: #046434;
  --blue: #1c1ca5;
}

.flag {
  width: 300px;
  height: 200px;
  display: flex;
  flex-direction: column;
  box-shadow: 0 0 1px rgba(0, 0, 0, 0.5);
}

.flag > * {
  flex: 1;
}

.saffron {
  background-color: var(--saffron);
}

.white {
  background-color: white;
  position: relative;
}
.green {
  background-color: var(--green);
}

.wheel {
  height: 100%;
  width: 67px;
  border-radius: 1in;
  margin: 0 auto;
  border: 2q solid var(--blue);
  position: relative;
  display: grid;
  place-items: center;
  -webkit-box-reflect: left -99%; /* play with value -99%, 100%, 101% */
}

.spoke {
  height: 50%;
  width: 2px;
  position: absolute;
  top: 0;
  clip-path: polygon(50% 0, 50% 0, 100% 70%, 50% 100%, 50% 100%, 0 70%);
  transform-origin: bottom;
  background-color: var(--blue);
}

.spoke:nth-child(1) {
  transform: rotate(15deg);
}

.spoke:nth-child(2) {
  transform: rotate(30deg);
}

.spoke:nth-child(3) {
  transform: rotate(45deg);
}

.spoke:nth-child(4) {
  transform: rotate(60deg);
}

.spoke:nth-child(5) {
  transform: rotate(75deg);
}

.spoke:nth-child(6) {
  transform: rotate(90deg);
}

.spoke:nth-child(7) {
  transform: rotate(105deg);
}

.spoke:nth-child(8) {
  transform: rotate(120deg);
}

.spoke:nth-child(9) {
  transform: rotate(135deg);
}

.spoke:nth-child(10) {
  transform: rotate(150deg);
}

.spoke:nth-child(11) {
  transform: rotate(165deg);
}

.spoke:nth-child(12) {
  transform: rotate(180deg);
}
</style>
</head>

<body>
<div class="flag">
    <div class="saffron"></div>
    <div class="white">
      <div class="wheel">
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
        <span class="spoke"></span>
      </div>
    </div>
    <div class="green"></div>
  </div>
</body>
</html>
