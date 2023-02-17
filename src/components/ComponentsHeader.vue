<template>
    
    <header>
        <div class="container">
            <nav class="navbar navbar-expand">
                <a href="" class="link navbar-brand mr-auto">
                    <img src="../assets/logo.png" alt="Footbal" class="img d-inline-block align-top" id="logo">
                </a>

                <div class="links mr-2">
                    <a href="#"  class="btn mr-5">Início</a>
                    <a href="#" class="btn mr-5">Times</a>
                    <a href="#" class="btn mr-5">Classificações</a>
                </div>
            </nav>
        </div>
    </header>


</template>

<script>

    export default {
        name: 'ComponentsHeader'
    }

</script>

<style scoped>
    header {
        background-color: rgb(6, 20, 50);
    }
    #logo {
        width: 100px;
        height: 100%;
        z-index: 2;
    }

    .links {
        display: inline-flex;
    }

    .links a {
        color: white !important;
        font-family: 'Tourney';
        font-size: 25px;
        text-transform: uppercase;
    }

    .links a:focus {
        outline:0pc !important;
    }

</style>