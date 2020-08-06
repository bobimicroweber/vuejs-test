<template>

  <div>
    <b-btn variant="success"><b-icon-chat></b-icon-chat> Hello, {{name}} </b-btn>
  </div>

</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      name: 'Bozhidar'
    }
  }
}
</script>
