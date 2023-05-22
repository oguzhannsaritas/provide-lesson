<template>
    <p>Component C</p> <hr>
        
    <p> {{ username }}</p> 
</template>
<script>

export default{
    inject:['username']
}



</script>