<script setup>
import Menu from './Menu.vue';
import BasicInformation from './BasicInformation.vue';
</script>

<template>

<div class="Menu">
    <Menu> </Menu>
</div>

<div class="Content">
    <BasicInformation></BasicInformation>
</div>

</template>

<style scoped>

.Menu{
    position: fixed;
    left: 0;
    top: 10px;;
}

.Content{
    position: fixed;
    right: 0;
    top: 0;
}

</style>
