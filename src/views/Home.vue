<template>
  <div class="home">
    <MyCalendar />
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// @ is an alias to /src
import MyCalendar from "@/components/MyCalendar.vue";

export default {
  name: "Home",
  components: {
    MyCalendar
  }
};
</script>
