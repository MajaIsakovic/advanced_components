<template>
    <div> 
      <h3>{{ quoteMessage }}</h3>
    </div>
</template>

<script>
    export default {
        data: function(){
          return{
            quoteMessage: "The Author component"
          }
        }
    }
</script>

<style scoped>
    div{
        border: 2px solid #5cb85c;
        background: #5cb85c;
        color: #fff;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
        border-radius: 3px;
    }
</style>