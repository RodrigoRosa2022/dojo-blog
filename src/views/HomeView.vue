<template>
  <div class="home">
    home
    <p>My name is {{name}} and my age is {{age}}</p>
    <button @click="handleClick">Click me</button>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  setup() {
    console.log('setup')

    let name = 'marioh'
    let age = 30

    const handleClick = () => {
      console.log('you clicked me')
    }

    return { name, age , handleClick}
  }
}
</script>
