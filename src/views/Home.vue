<template>
  <Layout/>
</template>

<script lang="ts">
// @ is an alias to /src
import Layout from '@/layout/Index.vue'
import { Component, Vue } from 'vue-property-decorator'

@Component({
  components: {
    Layout
  }
})

export default class Home extends Vue {

}
</script>
