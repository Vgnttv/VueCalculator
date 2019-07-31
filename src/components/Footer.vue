<template>
  <footer>
    <a href="https://www.linkedin.com/in/ottavia-vignani/" class="fa fa-linkedin" target="_blank"></a>
    <div class="Credits"> © Ottavia Vignani</div> 
  </footer>
</template>
<style scoped>
footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
  height: 50px;
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
  height: 100px;
}
footer:hover > .Credits {
  font-size: 40px;
}
.fa {
  padding: 0.66rem;
  font-size: 0.66rem;
  width: 0.66rem;
  text-align: center;
  text-decoration: none;
  margin: 0.16rem 0.06rem;
  border-radius: 100%;
}

.fa:hover {
    opacity: 0.7;
}

.fa-linkedin {
  background: rgb(0,123,181);
  color: white;
}
</style>
