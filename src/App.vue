<template>
    <div id="app">
        <MyHeader/>
        <MyContent/>
        <MyFooter/>
    </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue';
import MyContent from './components/MyContent.vue';
import MyFooter from './components/MyFooter.vue';


export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyFooter,
  } 
}
</script>

<style lang="scss">

</style>
