<template>
    <div class="rascunho">
        <AppNavBar />

        <h1>Rascunho</h1>

        <AppFooter />
    </div>
</template>

<script>
import AppNavBar from '@/components/layout/AppNavBar.vue';
import AppFooter from '@/components/layout/AppFooter.vue';

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