<template>
<h1>Root App Component</h1> 
<p>{{ username }}</p>
<hr>

<component-a/>
    
  
</template>

<script>
import ComponentA from './components/ComponentA.vue';

export default{
  components:{ComponentA},
  data(){
    return{
      username:'john'
    }
  },
  provide(){
    return{
      username:this.username
    }
  }
}

</script>