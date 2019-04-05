<template>
    <div class="container">
        <nav class="row ">
            <ul>
                <li class="">
                    <a href="url">
                        Inicio
                    </a>
                </li>
                <li class="">
                    <a href="url">
                        Mejores articulos
                    </a>
                </li>
                <li class="">
                    <a href="url">
                        Nuevos articulos
                    </a>
                </li>
                <li class="">
                    <a href="url">
                        Sobre nosotros
                    </a>
                </li>
            </ul>
        </nav>
    </div>
</template>
<script>
    export default {
        name: 'NavTop',

    }
</script>
<style scoped>

nav{
    margin-top: 50px;
    float: right;
}
ul{
    padding: 20px;
}
li{
    display: inline;
    margin-left: 20px;
    margin-right: 20px;
    font-size:30px;
}
    a{
        text-decoration: none;
        color:black;
    }
    a:hover{
        text-decoration: none;
        color:red;
        transition: 0.5s all;
    }
</style>
