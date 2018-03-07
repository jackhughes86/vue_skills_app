<template>
  <div class="about">
    <p>Your Name:</p><input v-model="their_name">
    <h1>Hello {{ their_name }}, This is an about page</h1>
    <p>My name is Keith, I have been working in web development
      for nearly 5 years and this is my Vue of life! Welcome!
    </p>
  </div>
</template>

<script>
export default {
  name: 'about',
  data() {
    return {
      their_name: 'You'
    }
  }
}
</script>