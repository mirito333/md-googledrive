<template>
    <div class="marked" v-html="tttt"></div>
</template> 

<script lang="ts">
  import {marked} from 'marked';


  const mdText = require("/markdowns/test.md");
  console.log(mdText)
  export default {
    setup(){
        const tttt = marked(mdText.default);
        return {
            tttt
        }
    }
  };
</script>