<template>
    <div class="navbar">
        <nav>
            <router-link to="/">Home</router-link>
            <router-link to="/about">About</router-link>
            <router-link to="/contacts">Contacts</router-link>
        </nav>
    </div>
</template>

<script>
export default {
    setup() {



        return {

        }
    }
}
</script>

<style scoped>
nav {
    background-color: black;
    color: white;
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 10px;
}

nav a {
  color: white;
  text-decoration: none;
  transition: 0.2s;
}

nav a:hover {
  color: gray;
}
</style>