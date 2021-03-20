<template>
  <div id="app" class="container">
    <MyNavbar />

    <router-view />
  </div>
</template>

<script>
import MyNavbar from "./views/navbar.vue";
export default {
  components: { MyNavbar },
};
</script>