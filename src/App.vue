<template>
    <div id="app" class="small-container">
    <h1>Books</h1>

    <books-table />
  </div>
</template>

<script>
  import BooksTable from '@/components/BooksTable.vue'

export default {
  name: 'App',
  components: {
    BooksTable,
  }
}
</script>

<style>
button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
  
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
