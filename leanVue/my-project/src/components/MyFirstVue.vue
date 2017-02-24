<template>
    <div class="myFirstVue">
      <h1>{{ msg }}</h1>
      <h2>My First Vue Template</h2>
    </div>
</template>
<style>
    body{
        background-color:#ffffff;
    }
    h1, h2 {
        font-weight: 1000px;
    }
</style>
<script>
export default {
  name: 'myFirstVue',
  data () {
    return {
      msg: 'AAAAAAA'
    }
  }
}
</script>
