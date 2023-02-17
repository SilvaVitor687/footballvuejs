<template>
    
    <section>
        <div class="container">
            <ComponentsSectionNewsIndividual 
                img-name="News1.jpg"
                img-info="Noticia 1"
                news-title="Clássico Eletrizante"
                news-content = "Em campo, o empate por 2 a 2 não mudou muito a situação do Corinthians no Paulistão. Líder do Grupo C, 
                                o time se garante na próxima fase se vencer o Mirassol no domingo, às 18h30 (de Brasília), em Itaquera."           
                
            />
            <ComponentsSectionNewsIndividual
                img-name="News_2.jpg"
                img-info="Noticia 2"
                news-title="Dia de Clássico"
                news-content = "Jogo será eletrizante, Corinthians x Palmeiras"
            />
            <ComponentsSectionNewsIndividual
                img-name="News_3.jpg"    
                img-info="Noticia 3"
                news-title="Preparação para o Jogo"
                news-content = "Treinos"
            />
        </div>
    </section>
    

</template>

<script>

    import ComponentsSectionNewsIndividual from './ComponentsSectionNewsIndividual.vue';

    export default {
        name: 'ComponentsSectionNews',
        components: {
            ComponentsSectionNewsIndividual
        }
        
    }

</script>

<style scoped>

section {
    padding: 100px;
    margin-top: 25px;
    background-color: rgb(50, 48, 54);
}

</style>