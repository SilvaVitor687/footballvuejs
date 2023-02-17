<template>
  <div class="app">
      <ComponentsHeader />
      <ComponentsSection />
      <ComponentsFooter />

  </div>
  
  
</template>

<script>
  import ComponentsHeader from './components/ComponentsHeader.vue';
  import ComponentsFooter from './components/ComponentsFooter.vue';
  import ComponentsSection from './components/ComponentsSection.vue';


export default {
  name: 'App',
  components: {
    ComponentsHeader,
    ComponentsFooter,
    ComponentsSection
   
  }
}
</script>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Roboto:wght@700&family=Tourney:wght@500&display=swap');
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Raleway:wght@200;500;700&family=Roboto:wght@700&family=Tourney:wght@500&display=swap');
 
</style>
