<template>
    <div> 
        <h3>{{ quoteMessage }}</h3>
    </div>
</template>

<script>
    export default {
        data: function(){
            return{
            quoteMessage: "The quote content component"
            }
        }
    }
</script>

<style scoped>
    div{
        border: 2px solid red;
        background: #d43f3a;
        color: #fff;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
        border-radius: 3px;
    }
    .title{
        font-size: 24px;
    }
</style>