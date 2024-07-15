<template>
    <div>
        <h1>{{ message }}</h1>
        <button @click="updateMessage">Update Message</button>
    </div>
</template>

<script>

export default {
    data() {
        return {
            message: 'sdfsdfsdfddddddddddddddddddddsdf!!'
        }
    },
  methods: {
    updateMessage() {
      this.message = 'Updated Message!';
    }
  }
}
</script>
