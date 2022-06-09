<template>
 
 <div>
<h1>Welcome to the best corny dad jokes on the app</h1>
 </div>
  
</template>

<script lang="ts">
import Vue from 'vue'

// export default Vue.extend({
//   name: 'IndexPage',
// })


export default {

    head(){
        return {
            title: 'Welcome to dad jokes',
            meta: [
                {
                    hid: 'description',
                    name: 'description',
                    content: 'Best place for corny dad jokes'
                }
            ]
        }
    }

}

</script>
