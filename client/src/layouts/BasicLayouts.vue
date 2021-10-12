<template>

    <div>
        <header>

    <div class="basic-layout">
    <Menu />
    

    <div class="ui container">
        <slot />
    </div>
    </div>
     </header>
   </div>

</template>

<script>
import Menu from '../components/Menu.vue';

export default {
    name : "BasicLayouts",
    components: {
        Menu,
    },
};
</script>

<style>



</style>