<template>
  <div>
    <h1>Photo List1</h1>
    <button @click="test">test!!</button>
  </div>
</template>
<script>
export default {
  data() {
    return {
      text: 'example'
    }
  },
  methods : {
    test () {
      alert("test!")
    }
  }
}
</script>