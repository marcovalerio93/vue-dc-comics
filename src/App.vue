<template>
    <div id="app">
        <MyHeader/>
        <MyContent/>
        <MyFooterTop/>
    </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue';
import MyContent from './components/MyContent.vue';
import MyFooterTop from './components/MyFooterTop.vue';


export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyFooterTop,
  } 
}
</script>

<style lang="scss">

</style>
