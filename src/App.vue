<template>
  <div id="app">
    <h1>Calculator</h1>
    <Calculator />
  </div>
</template>

<script>
import Calculator from "./main/Calculator";

export default { 
    components: {Calculator }
    };
</script>

<style>
@font-face {
  font-family: "RobotoMono";
  src: url("./fonts/RobotoMono-Thin.ttf");
}

* {
  font-family: "RobotoMono", monospace;
}

body {
  margin: 0;
}

#app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: #fff;
  background: rgb(197, 255, 215);
  background: linear-gradient(
    90deg,
    rgba(197, 255, 215, 1) 0%,
    rgba(45, 208, 156, 1) 74%,
    rgba(112, 224, 176, 1) 100%
  );
}
</style>