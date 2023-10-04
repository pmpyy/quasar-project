# IndexPage.vue
<template>
  <div class="htmlClass">
    <h1>{{ title }}</h1>
    <InputPage></InputPage>
    <FunctionPage></FunctionPage>
  </div>
</template>


<script>
import InputPage from './InputPage.vue';
import FunctionPage from './FunctionPage.vue'
export default {

  name: 'HtmlComponent',
  components:{
    InputPage,
    FunctionPage
  },
  data() {
    return {
      title: 'Pimonpaan',
    }
  },
}
</script>

<style scoped></style>
