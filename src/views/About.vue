<template>
  <div class="about">
    <h1>This is an about page</h1>
    <div>{{name}}</div>
    <AboutDetail />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import AboutDetail from "@/components/AboutDetail.vue";
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "about",
  data() {
    return {
      name: "asdf"
    };
  },
  components: {
    AboutDetail
  }
};
</script>