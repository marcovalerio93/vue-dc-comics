<template>
  <div class="card">
    <img :src="details.thumb"/>
    <h3>{{details.series}}</h3>

  </div>
</template>

<script>
export default { 
    name: "SingleProduct",
    props:{
        imageSrc: String,
        title: String,

    }

}
</script> 

<style scoped lang="scss">
    .card{
        flex-basis: 15%;
        padding: 10px;
        
        img{
            max-width: 100%;
        }
        h3{
            font-size: 16px;
            color: #fff;
        }
        }

</style>