<template>
    <div class="notfound">
        <h1>404</h1>
        <h2>Oops! Página não encontrada</h2>
        <p>A página que você está procurando não foi encontrada.</p>
        <router-link to="/">Voltar para a página inicial</router-link>
    </div>
</template>

<script>
export default {
    setup() {



        return {

        };
    }
};
</script>

<style scoped>
.notfound {
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column
}
</style>
