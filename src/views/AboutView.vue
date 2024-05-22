<template>
    <div class="about">
        <AppNavBar />

        <h1>About</h1>

        <AppFooter />
    </div>
</template>

<script>
import AppFooter from '@/components/layout/AppFooter.vue';
import AppNavBar from '@/components/layout/AppNavBar.vue';

export default {
    components: {
        AppNavBar,
        AppFooter
    },

    setup() {



        return {

        }
    }
}
</script>

<style scoped></style>