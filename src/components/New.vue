<template>
    <div> 
        <h3>{{ quoteMessage }}</h3>
    </div>
</template>

<script>
    export default {
        data: function(){
            return{
                quoteMessage: "New quote component"
            }
        }
    }
</script>

<style scoped>
    div{
        border: 2px solid #46b8da;
        background: #5bc0de;
        color: #fff;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
        border-radius: 3px;
    }
</style>