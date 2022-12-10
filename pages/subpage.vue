<template>
  <div>
    <MarkDown :filepath= "filepath"/>
  </div>
</template> 

<script lang="ts">
  import MarkDownVue from '../components/MarkDown.vue';
  export default{
    components: { MarkDownVue },
    data(){
      return {
        filepath: 'subpage.md'
      }
    }
  }
</script>