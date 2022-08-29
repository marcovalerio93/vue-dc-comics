<template>
  <div>
    <a href="#"><span>SING-UP-NOW</span></a>
    <div class="social">
      <span class="right">FOLLOW US</span>
      <img src="../assets/img/footer-facebook.png">
      <img src="../assets/img/footer-periscope.png">
      <img src="../assets/img/footer-pinterest.png">
      <img src="../assets/img/footer-twitter.png">
      <img src="../assets/img/footer-youtube.png">

    </div>
    
  </div>
</template>

<script>
export default {
    name:'MyFooterDown',

}
</script>

<style scoped lang="scss">
div{
  font-family: sans-serif;
  height: 70px;
  background-color:#474646 ;
  display: flex;
  justify-content: space-around;
  
  a{
    margin: 10px;
    text-decoration: none;
    color: #fff;
    font-size: 20px;
    font-weight: 600;
    border: solid 1px #0c7cec;  
    padding: 10px;
  }

  .social{
    .right{
    font-size: 20px;
    font-weight: 600;
    color:#0c7cec ;
    margin: 20px;

    img{
      height: 10px;
      margin-left:10px;
    }
  }


  }

  



}

</style>