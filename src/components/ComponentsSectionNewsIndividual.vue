<template>

    <div class="row">

        <div class="col-3">
            <img :src="('/img/' + this.imgName)" :alt="imgInfo">
        </div>
        <div class="col-9">
            <h2>{{ newsTitle }}</h2>
            <p>{{ newsContent }}</p>

        </div>
    </div>
     
</template>

<script>

    export default {
       
        props: {
            imgName: {
                type: String,
                required: true
            },
            imgInfo: {
                type: String,
                required: true
            },
            newsTitle: {
                type: String,
                required: true
            },
            newsContent: {
                type: String,
                required: true
            }

        }
              
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