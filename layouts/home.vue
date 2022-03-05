<template>
  <div class="body-content">
    <!-- <section class="hero is-fullheight bg-img" id="header"> -->
    <section class="hero bg-img" id="header">
      <div class="hero-head">
        <nav-bar></nav-bar>
      </div>
      <div class="hero-body">
        <div class="typer-title">
          <client-only>
            <vue-typer
              class="subtitle"
              id="does-things"
              :pre-type-delay="600"
              :type-delay="70"
              :pre-erase-delay="10000"
	      erase-delay="70"
              erase-style="backspace"
              :text="[
              'the swan group'
              ]"
            ></vue-typer>
          </client-only>
        </div>
      </div>
    </section>
    <div id="main">
      <nuxt/>
    </div>
    <my-footer></my-footer>
  </div>
</template>

<script>
import NavBar from "~/components/NavBar.vue";
import MyFooter from "~/components/MyFooter.vue";
// if (process.browser) {
//   require "~/plugins/particles."
// }
export default {
  components: {
    NavBar,
    MyFooter,
  },
};
</script>

<style lang="scss">
</style>
