<template>
  <section class="container">
    <h1>Top Page</h1>
    <p>{{ message }}</p> 
    <hr>
      <router-link to="/price">Price Page</router-link>
    </hr>
  </section>
</template>

<script>
export default {
  data: function() {
    return {
      message: "Hello World!"
    }
  }
}
</script>
