<template>
    
    <section>
        <div class="container">
            <ComponentsSectionNewsIndividual />
            <ComponentsSectionNewsIndividual />
            <ComponentsSectionNewsIndividual />
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