<template>
     <section>
        <div class="container">
            <div class="row">
                <div class="col-5 text-center principal-news" >
                    <h2>Veja os ultimos Resultados</h2>
                </div>
                <div class="col-5 offset-2 text-center principal-news ">
                    <h2>Venha conhecer o centro de treinamento sFootballs</h2>

                </div>
            </div>
        </div>
     </section>

</template>

<script>

    export default {
        name: 'ComponentsSectionBanner'
    }

</script>

<style scoped>

section {    
    margin-top: 100px;
}

.container .row {
    height: 300px;
}

.container  .row .col-5:first-child {
    background-color: rgba(0, 0, 0, 0.5);
    background-image: url('/public/img/Football_Prof.jpg');
    background-repeat: no-repeat;    
    border-radius: 10px;
}

.container  .row .col-5:nth-child(2) {
    background-color: rgba(0, 0, 0, 0.5);
    background-image: url('/public/img/Football_Centro.jpg');
    background-repeat: no-repeat;
    background-size: 100%;    
    border-radius: 10px;
}

h2 {
    margin: 25% 0 ;
    color: white;
    background-color: rgba(0, 0, 0, 0.8);
    padding: 10px;
    border-radius: 10px;
    text-transform: capitalize;
}

.principal-news {
    cursor: pointer;
}
   

</style>