<template>
<footer class="footer has-text-light">
  <div class="container">
    <div class="columns">
      <div class="column is-2 has-text-centered">
        <img src="/imgs/swan-logo.png" style="max-height: 125px;">
      </div>
      <div class="column content">
        <vue-markdown>
The Swan Group

Department of Chemical Engineering

Massachusetts Institute of Technology

4.101 Science and Engineering Complex
150 Western Ave
Boston, MA 02134
        </vue-markdown>
      </div>
    </div>

  </div>
</footer>
</template>

<script>
import VueMarkdown from "vue-markdown";
export default {
  components: {
    VueMarkdown,
  },
};
</script>

<style lang="scss">
</style>
