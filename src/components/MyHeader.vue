<template>
    <div>
        <header>
    <img src="@/assets/img/">
    <nav>
        <ul>
            <li v-for="(link, index) in pincopallino" :key="index" >
                <a :href="link.url" :class="link.active?'active':''" >{{link.text}}</a>
            </li>
        </ul>
    </nav>
  </header>
    </div>
</template> 

<script>
export default {
    name:'MyHeader',
}
</script>

<style>

</style>