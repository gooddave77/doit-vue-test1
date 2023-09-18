<template>
    <section id="wrap">
        <h1 class="bind">웹싸이트제목:VUE스터디</h1>
        <Header />
        <section>상단 영역</section>
        <section id="container">
            <router-view />
        </section>
        <Footer />
        <section>하단 영역</section>
    </section>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
export default {
    components: {
        Header,
        Footer,
    },
};
</script>