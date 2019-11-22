<template>
    <div> 
        <!-- add it to the child component you want to pass content -->
        <slot></slot>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
    div{
        border: 2px solid #ccc;
        padding: 30px;
        margin: 30px auto;
        text-align: center;
        border-radius: 3px;
        color: rgb(37, 37, 37);
    }
</style>