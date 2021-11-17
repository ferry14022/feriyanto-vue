<template>
<div style="background:#284988;">
    <div class="jumbotron text-center">
      <img src="123.jpg" width="250px" class="rounded-circle mt-4 mb-3" >
      <h1 style="color:white;">Feriyanto</h1>
      <p style="color:white;">Student || Professional Gamer</p>
    </div>
  <hr>
      <section class="about" id="about">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <h2 class="text-center" style="color:white;">About</h2>
            <hr>
          </div> 
        </div>

        <div class="row">
          <div class="col-sm-3">
            <p>  </p>
          </div>
          <div class="col-sm-6" style="color:white;">
            <p>I am Ferry, from a planet called Earth. I am 19 years old, I like noodles, I guess you could say that it's my favorite food. I'm a profesional Valorant player and I am currently playing for KAZE a profesional valorant team. I was BORN TO WIN.</p>
          </div>
          <div class="col-sm-3">
            <p>  </p>
          </div>
        </div>
      </div>
    </section>
    <hr>
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <h2 class="text-center" style="color:white;">More About Me</h2>
            <hr>
          </div>
        </div>

        <div class="row">
          <div class="col-md-6">
            <a href="https://instagram.com/peeyyyii?utm_medium=copy_link"><img src="instagram.png" width="22%" class="mt-4"></a>
          </div>

          <div class="col-md-6">
            <a href="http://nimo.tv/peyyyii"><img src="nimo.png" width="30%"></a>
          </div>
        </div>
      </div>
      <p style="color:#284988;">asa</p>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>