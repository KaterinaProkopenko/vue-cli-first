<template>
  <div class="hero">
    <div id="jumbotron">
        <h1>Jumbotron</h1>
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b6/Image_created_with_a_mobile_phone.png/640px-Image_created_with_a_mobile_phone.png">
        <img src="../assets/my-image.jpg">
    </div>
  </div>
</template>

<script>
export default {
  name: 'MyHero',
  data(){
    return{
      message: 'Il mio componente nuovo',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#jumbotron {
    width: 600px;
    height: 300px;
    background-color: red;
    margin: 0 auto;
}
img{
    width: 100px;
    height: 100px;
    display: block;
    margin: .4rem auto;
}
h1{
    padding-top: 1rem;
    color: white;
}
</style>