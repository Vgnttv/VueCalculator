<template>
  <footer>
    <div class="Credits"> © Ottavia Vignani</div>
  </footer>
</template>
<style scoped>
footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 90px;
  background-color: #2c3e50;
  color: white;
  transition-timing-function: ease-in-out;
  transition: height 1s;
  align-items: center;
  display: flex;
  justify-content:flex-end;
  
}
.Credits {
  transition-timing-function: ease-in-out;
  transition: font-size 1s;
  margin: 20px;
  
}
footer:hover {
  height: 200px;
}
footer:hover > .Credits {
  font-size: 60px;
}
</style>
