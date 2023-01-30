<template>
<div class="TopBar">
    <NavBar />
</div>
</template>

<style>
.TopBar{
    width: 100%;
    height: 100px;
    background-color: var(--nord1);
    margin-bottom: 10px;
}
</style>

<script>
import NavBar from './Navbar.vue'
export default{
    components:{
        NavBar
    }
}
</script>