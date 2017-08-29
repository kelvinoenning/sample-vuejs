<template>
  <div class="navbar">
    <div>
        <img src="../assets/vuejs.png" alt="vuejs" class="icon">
        VueJS
    </div>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
  div{
    display: flex;
    align-items: flex-end;
  }
  .navbar{
    width: 100%;
    background-color: rgba(0, 0, 0, 0.7);
    color: white;
    padding: 10px 25px;
    font-size: 1.4em;
    font-weight: bold;
  }
  .icon{
    max-width: 50px !important;
  }
</style>
