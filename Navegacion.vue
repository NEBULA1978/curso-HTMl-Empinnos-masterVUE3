<!-- Navegacion.vue -->
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
    name: 'Navegacion',
}
</script>

<style scoped>
/* Estilos específicos para este componente */
.contenedor-flex-1 {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333; /* Cambia el color de fondo según tu diseño */
    padding: 10px 20px; /* Añade espaciado interior */
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); /* Agrega una sombra */
    /* Añade otros estilos según tus preferencias */
}

.contenedor-flex-1 a {
    text-decoration: none;
    color: white; /* Cambia el color del texto de los enlaces */
    margin-right: 20px; /* Espaciado entre enlaces */
}

.contenedor-flex-1 a:hover {
    text-decoration: underline; /* Subraya los enlaces al pasar el mouse */
}
</style>
