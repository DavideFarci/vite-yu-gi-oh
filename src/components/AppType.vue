<script>
export default {};
</script>

<template>
  <div class="select-container">
    <select>
      <option selected>Type</option>
      <option value="opzione2">Opzione 2</option>
      <option value="opzione3">Opzione 3</option>
      <option value="opzione4">Opzione 4</option>
    </select>
  </div>
</template>

<style lang="scss" scoped>
.select-container {
  max-width: 1000px;
  margin: auto;
  select {
    padding: 0.5rem;
    margin: 1rem 0;
    font-size: 1.1em;
    font-weight: bold;
    border-radius: 5px;
  }
}
</style>
