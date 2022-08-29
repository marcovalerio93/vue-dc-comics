<template>

    <header>
        <img src="../assets/img/dc-logo.png">
        <nav>
            <ul>
                <li v-for="(link,index) in links" :key="index">
                    <a :href="link.url">{{link.text}}</a>
                </li>
            </ul>
        </nav>
    </header>

</template> 

<script>
export default {
    name:'MyHeader',
    data() {
        return{
            links: [
                {
                    text: 'CHARATERS',
                    url: '#', 
                    active: false
                },
                {
                    text: 'COMICS',
                    url: '#', 
                    active: true
                },
                {
                    text: 'MOVIES',
                    url: '#', 
                    active: false
                },
                {
                    text: 'TV',
                    url: '#', 
                    active: false
                },
                {
                    text: 'GAMES',
                    url: '#', 
                    active: false
                },
                {
                    text: 'COLLECTIBELS',
                    url: '#', 
                    active: false
                },
                {
                    text: 'VIDEOS',
                    url: '#', 
                    active: false
                },
                {
                    text: 'FANS',
                    url: '#', 
                    active: false
                },
                {
                    text: 'NEWS',
                    url: '#', 
                    active: false
                },
                {
                    text: 'SHOP',
                    url: '#', 
                    active: false
                },
            ]
        }
    }
}
</script>

<style lang="scss">
  header{
    display: flex;
    justify-content: space-around;
    padding: 30px;

    ul{
        list-style: none;
        margin: 20px;
        padding-top: 10px;

        li{
            display: inline-block;
            margin:  0px 10px;
            
            a{
                color: black;
                text-decoration: none;
                font-family: sans-serif;

            &:active{
                color: #0c7cec;
                border-bottom: solid 2px #0c7cec;
            }
            &:hover{
                color: #0c7cec;
            }             
            }
        }
    }
  }

</style>