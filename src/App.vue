<template>
    <Navbar :logoVindoDoPai="logo_src" :altVindoDoPai="app_name" />
    <router-view />
    <Footer />
</template>
<script>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';

export default {
    components: {
        Navbar,
        Footer
    },
    data(){
        return{
            logo_src: "/img/logo.png",
            app_name: "Monte seu BurgerBug"
        }
    }
}
</script>
