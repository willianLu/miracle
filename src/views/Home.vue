<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <a :a="1" :b="2" :c="3" :d="4" :e="5" :f="6" :g="7" :h="8"
      >kkkk <span>dd</span></a
    >
    <p>dddd</p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
  methods: {
    test() {
      console.log(111111111);
    },
  },
};
</script>
