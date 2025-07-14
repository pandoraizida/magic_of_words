<script setup>
//import HelloWorld from './components/HelloWorld.vue'
</script>

<template>

  <header>
   <div><img alt="logo" class="logo" src="./components/icons/cat1.jpg"/></div>
   <div class="greeting">Today's brilliant word for practice:</div>
  </header>

  <main>
    <div class="container">
      <div class="cont cont_word">
        <div class="wd wd_word">Word from Dictionary</div>
        <div class="wd wd_type">Word type</div>
      </div>
      <div class="cont cont_description">
        <div class="wd wd_desc">Word description hdsfhjkds fdsjkhfhsd dfsjfhhds dsjhafjkdsa dfshjkhfjkdas dsjfhdsajhfsda fadsjhfhsd</div>
        <div class="wd wd_example">Example how to use this word Example how to use this word Example how to use this word Example how to use this word. </div>
      </div>
    </div>
  </main>

  <footer>
    Have fun!
  </footer>
</template>

<style scoped>

header {
  height: 10%;
  width: 100%;
  display: flex;
  flex-direction: row;
  padding: 30px;
}

.logo {
  flex-basis: 30%;
}

.greeting {
  font-size: 38px;
  color: rgb(69, 6, 94);
  font-weight: 800;
  text-align: center;
  flex-basis: 70%;
  padding-top: 90px;
}

main {
  width: 100%;
  height: 100%;
}

.container {
  display: flex;
  width: 100%;
  height: 100%;
  flex-direction: row;
}

.cont {
  display: flex;
  flex-direction: column;
}

.cont_word {
  flex-basis: 40%;
}

.cont_description {
  flex-basis: 60%;
}

.wd {
  text-align: left;
  font-size: 30px;
  color: rgb(69, 43, 93);
  padding: 30px;
}

.wd_word {
  padding: 70px 30px 30px 30px;
  font-weight: bold;
  font-size: 35pt;
  color: rgb(38, 2, 2);
}

.wd_type {
  font-size: 15px;
  color: rgb(45, 1, 41);
}

.wd_desc {
  padding: 80px 30px 30px 30px;
}

footer {
  font-size: 35px;
  color: rgb(69, 6, 94);
  font-weight: 800;
  text-align: center;
  height: 5%;
  margin-top: 80px;
}

</style>
