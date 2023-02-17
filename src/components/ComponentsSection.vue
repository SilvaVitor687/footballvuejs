<template>
    <div>
        <ComponentsSectionBanner />
        <ComponentsSectionNews />
    </div>
    
</template>

<script>
    import ComponentsSectionBanner from './ComponentsSectionBanner.vue';
    import ComponentsSectionNews from './ComponentsSectionNews.vue';
    export default {
        name: 'ComponentsSection',
        components: {
            ComponentsSectionBanner,
            ComponentsSectionNews
        }
    }

</script>

<style>


</style>