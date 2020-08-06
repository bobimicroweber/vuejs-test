<template>

  <div>

    <br />
    <b-btn variant="success" v-b-tooltip.hover title="Tooltip directive content"><b-icon-chat></b-icon-chat> Hello, {{name}} </b-btn>
    <br />
    <br />
    <b-input v-model="name"></b-input>
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
