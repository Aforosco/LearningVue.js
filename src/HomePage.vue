<template>
 <main>
  <div class ="home">
    <div>
    <img class = "robot" src = "../assets/robot-home.png" aria-hidden="true" alt="robot"/>
    </div>
    <div class="get-started">
      <a href="">Get Started</a> BUILD YOUR FIRST ROBOT!
    </div>

   </div>

  </main>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.home {
  text-align: center;
}
.robot {
height: 500px;

}

.get-started{
 padding-top: 20PX;
 font-size: 35PX;

}
</style>
