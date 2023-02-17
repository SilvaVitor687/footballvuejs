<template>

    <div class="row">

        <div class="col-3">
            <img src="../assets/News_1.jpg" alt="">
        </div>
        <div class="col-9">
            <h2>Hoje tem Clássico é guerra - 16/03/2023</h2>
            <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. 
                Cumque dolore saepe aperiam officiis, eos delectus eum ullam praesentium maiores tempora. 
                Quaerat, cumque amet sunt tempora est molestias fugiat accusamus facere.</p>

        </div>
    </div>
     
</template>

<script>

    export default {
        name: 'ComponentsSectionNewsIndividual'
    }

</script>

<style scoped>
    .row {

        margin-bottom: 30px;
        
    }

    img {
        width: 100%;
        border-radius: 15px;
    }

    h2 {
        cursor: pointer;
        color: white;
        text-transform: uppercase;
        font-weight: bolder;
        font-family: 'Raleway';
    }

    p {
        color: bisque;
        font-family: 'Raleway';
    }
</style>