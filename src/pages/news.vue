<template>
  <q-page padding>
    <news />
  </q-page>    
</template>

<script>

import News from '../components/news/list'
export default {
   name: 'NewsPage',
   components: {
     News
   }
}
</script>