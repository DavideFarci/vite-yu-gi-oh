<script>
import AppList from "./components/AppList.vue";
import AppType from "./components/AppType.vue";
export default {
  components: {
    AppType,
    AppList,
  },
};
</script>

<template>
  <header>
    <div>
      <img src="" alt="" />
      <h1>Yu-Gi-Oh Api</h1>
    </div>
  </header>

  <!-- sfondo arancione -->
  <main>
    <!-- sfondo bianco  -->
    <div class="main_container">
      <AppType />
      <div class="cards_list">
        <!-- componente Lista con dentro componente card e founded  -->
        <AppList />
      </div>
    </div>
  </main>
</template>

<style lang="scss"></style>
