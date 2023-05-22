<template>
<p>Component A</p>
<p>{{ username }}</p>
<hr>

        <component-b/>
    
</template>

<script>

import ComponentB from "./ComponentB.vue";
export default{
    components:{ComponentB},
    inject:['username']
}

</script>