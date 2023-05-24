<script>
import { store } from "../store";
export default {
  data() {
    return {
      store,
    };
  },
};
</script>

<template>
  <div class="founded">Found {{ store.AppList.length }} cards</div>
</template>

<style scoped>
.founded {
  background-color: black;
  color: white;
  height: 3rem;
  padding: 0.9rem;
}
</style>
