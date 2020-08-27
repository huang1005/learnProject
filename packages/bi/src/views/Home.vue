<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <biPreview msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
// @ is an alias to /src
// import biPreview from "bi-preview";
import lodash from 'lodash'
export default {
  name: 'Home',
  components: {
    biPreview
  }
}
</script>
