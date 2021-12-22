<template>
  <div>
    <h1>Hello from home components</h1>
    <!-- <button v-on:click="hello('hello World')">Click Me</button> -->
    <h1 v-if="show">Click Me if</h1>
    <h1 v-else>Click Me else</h1>
    <button v-on:click="display">Click Me</button>
  </div>
</template>
<script>
export default {
  name: 'Home',
  props: {
    data: String,
    msg: String,
  },
  // methods: {
  //   hello(string) {
  //     alert(string)
  //   },
  // },
  data() {
    return { show: true }
  },
  methods: {
    display() {
      this.show = !this.show
    },
  },
  // asyncData(context) {
  //   // if (process.server) {
  //   //   console.log('hi i  a server')
  //   // }
  //   // return { blah: 'h1' }
  // },
  // middleware: 'erik',
}
</script>
<style></style>
