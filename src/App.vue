<template>
  <div class="wrapper">
    <PageHeader/>
    <router-view/>
    <PageFooter/>
  </div>
</template>

<script>
  import PageHeader from './components/PageHeader'
  import PageFooter from './components/PageFooter'

  export default {
    name: 'App',
    components: {
      PageHeader,
      PageFooter,
    }
  }
</script>

<style lang="scss">

  * {
    box-sizing: border-box;
  }

  body {
    margin: 0;
  }

  .container {
    width: 960px;
    margin-right: auto;
    margin-left: auto;
    padding-left: 10px;
    padding-right: 10px;
  }

</style>
