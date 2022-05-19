<template>
  <div class="container">
    <div class="header">
      <slot name="header" /></div>
    <div class="body">
      <slot name="body" /></div>
    <div class="footer">
      <slot name="footer" /></div>
  </div>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
  flex-direction: column;
  width: 100%;
  align-content: center;
  justify-content: center;
  .header {
    width: 100%;
    height: 200px;
    background-color: red;
  }
  .body {
    width: 100%;
    height: 50px;
    background-color: blue;
  }
  .footer {
    width: 100%;
    height: 50px;
    background-color: yellow;
  }
}
</style>
