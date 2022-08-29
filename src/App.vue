<template>
    <div id="app">
        <MyHeader/>
        <MyContent/>
        <MyBonus/>
        <MyFooterTop/>
        <MyFooterDown/>
    </div>
</template>

<script>

import MyHeader from './components/MyHeader.vue';
import MyContent from './components/MyContent.vue';
import MyBonus from './components/MyBonus.vue';
import MyFooterTop from './components/MyFooterTop.vue';
import MyFooterDown from './components/MyFooterDown.vue';

export default {
  name: 'App',
  components: {
    MyHeader,
    MyContent,
    MyBonus,
    MyFooterTop,
    MyFooterDown,
  } 
}
</script>

<style lang="scss">

</style>
