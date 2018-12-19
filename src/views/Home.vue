<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <IssueTracker msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
import IssueTracker from "@/components/IssueTracker.vue";

export default {
  name: "home",
  components: {
    IssueTracker
  }
};
</script>
