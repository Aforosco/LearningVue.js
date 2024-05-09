<template>
  <main>
    <header>
      <nav>
        <ul>
          <li class="nav-item">
            <img class="logo" src="./assets/build-a-bot-logo.png" alt="logo"/>
            Build-a-bot
          </li>
        </ul>
      </nav>
    </header>
  <!--<HomePage msg ="Welcome to your vue.js app"/>-->
  <RobotBuilder/>
  </main>
</template>

<script>
import RobotBuilder from './build/RobotBuilder.vue';

export default {
  name: 'App',
  components: {
    RobotBuilder,
  },
};
</script>

<style>
#app {
  font-family: Avenir,Helvetica,Arial,sans-serif;
}
body{
  background: linear-gradient(to bottom, #555 ,#999);
  background-attachment: fixed;
}
main{
  margin: 10px auto;
  padding: 30px;
  background-color: white;
  width: 1400px;
  min-height: 300px;
}
header{
  background-color: #999;
  width: 1300px;
  margin: 0 auto;
}

ul {
 display: flex;
 padding: 3px;
}

.nav-item {
 display: inline-block;
 padding: 5px 10px;
 font-size: 20px;
 border-right: 1px solid #bbb;
}
.logo{
  vertical-align: middle;
  height: 30px;
}
</style>./home/HomePage.vue./HomePage.vue
