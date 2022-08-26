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
                    acttive: false
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
                    acttive: false
                },
                {
                    text: 'NEWS',
                    url: '#', 
                    acttive: false
                },
                {
                    text: 'SHOP',
                    url: '#', 
                    acttive: false
                },
            ]
        }
    }
}
</script>

<style>

</style>