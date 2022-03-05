<template>
    <div class="default-layout">
      <nav-bar></nav-bar>
      <div class="body-content">
      <nuxt/>
      </div>
      <my-footer></my-footer>
    </div>
</template>

<script>
import NavBar from "~/components/NavBar.vue";
import MyFooter from "~/components/MyFooter.vue";
export default {
  components: {
    NavBar,
    MyFooter,
  }
};
</script>
