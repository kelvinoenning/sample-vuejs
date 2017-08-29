<template>
  <div class="box">

    <div>
      <div>
        <img src="../assets/npm.png" alt="npm">
      </div>

      <div class="description">
        {{msg}}
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Hands-on?'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" scoped>
  .box
    display: flex;
    align-items: center;
    justify-content: space-around;

    .description
      font-weight: bold;
      font-size: 2em;
      margin-top: 25px;

</style>
