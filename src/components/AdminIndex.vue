<template>
  <div class="body">
    <Header/>
    <div class="layoutRight">
        <MenuVue/>
        <div>
            <MainVue/>
            <FooterVue/>
        </div>
    </div>
  </div>
</template>

<script setup>
    import FooterVue from "./layout/Footer.vue"
    import Header from "./layout/Header.vue"
    import MainVue from "./layout/Main.vue"
    import MenuVue from "./layout/Menu.vue"

</script>

<style scope>
.body{
    width:100%;
    border: 1px solid black
}
.layoutRight{
    display: flex;
    width: 100%;
}
</style>