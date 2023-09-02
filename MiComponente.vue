<template>
    <nav class="contenedor-flex-1">
        <a href="index.html">
            <img src="img/logo.png" alt="logo" width="250" height="50">
        </a>
        <ul>
            <router-link to="/">
                <li><a href="index.html">Inicio</a></li>
            </router-link>
            <router-link to="/contacto">
                <li><a href="nosotros.html">Nosotros</a></li>
            </router-link>
            <router-link to="/nosotros">
                <li><a href="contacto.html">Contacto</a></li>
            </router-link>
            <router-link to="/somos">
                <li><a href="somos.html">Somos</a></li>
            </router-link>
        </ul>
    </nav>
</template>

<script>
export default {
  // Component logic here
}
</script>

<style scoped>/* Component-specific styles here */</style>
