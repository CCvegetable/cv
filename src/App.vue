<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header>
    <div class="test">
      <img alt="Vue logo" class="logo" :src="`./photo.JPG`" height=450 />
    </div>

    <div class="wrapper">
      <HelloWorld msg="蔡涵伃 Han Yu, Tsai" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
    border-radius: 10%;
    -moz-border-radius: 10%;
   -webkit-border-radius: 10%;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}

.test {
  height: 85%;

}
</style>
