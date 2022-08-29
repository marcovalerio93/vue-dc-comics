<template> 
    <div>
        <ul>
            <h3>DC COMICS</h3>
            <li>Charater</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>video</li>
            <li>news</li>
        </ul>
        <ul>
            <h3>SHOP</h3>
            <li>Charater</li>
            <li>comics</li>
        </ul>
        <ul>
            <h3>DC</h3>
            <li>Charater</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
            <li>games</li>
            <li>video</li>
            <li>news</li>
            <li>Charater</li>
            <li>comics</li>
        </ul>
        <ul>
            <h3>Sites</h3>
            <li>Charater</li>
            <li>comics</li>
            <li>movies</li>
            <li>tv</li>
        </ul>
        <img src="../assets/img/dc-logo-bg.png" alt="logo">
        
    
        
    </div>
    
</template>

<script>
export default {
    name: 'MyFooterTop',

}
</script>

<style scoped lang="scss">
div{
    height: 480px;
    background-image: url('../assets/img/footer-bg.jpg');
    display: flex;
    justify-content: space-around;
    font-family: sans-serif;

    ul{
       list-style: none;
        margin: 20px;
        padding-top: 10px;

        h3{
            color: #fff;;
        }
        li{
            color: gray;
        }
    }
}


</style>