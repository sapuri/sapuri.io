<template>
  <div class="home">
    <header>
      <md-toolbar class="md-transparent">
        <h1 class="md-title">sapuri.io</h1>
      </md-toolbar>
    </header>

    <Profile title="sapuri.io" />

    <footer><p>&copy; 2018 sapuri.io</p></footer>
  </div>
</template>

<script>
import Vue from "vue";
import { MdToolbar } from "vue-material/dist/components";

Vue.use(MdToolbar);

// @ is an alias to /src
import Profile from "@/components/Profile.vue";

export default {
  name: "home",
  components: {
    Profile
  }
};
</script>

<style scoped lang="stylus">
header
  position sticky
  position -webkit-sticky
  top 1px
  z-index 10

footer
  margin-bottom 20px
</style>
