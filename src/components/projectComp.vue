<template>
  <div class="about-us__project-item">
    <div>
      <img src="../assets/img/icons/console.svg" alt="">
      <h2>{{ title }}</h2>
    </div>

    <p>{{ info }}</p>
  </div>
</template>

<script>
  export default {
    name: 'projectComp',
    props:{
      title: String,
      info: String
    }
  }
</script>