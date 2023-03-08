<template>
  <div class="project__item">
    <img src="../assets/img/icons/project.svg" alt="">

    <div>
      <h3>{{ headtext }}</h3>
      <p>{{ msg }}</p>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'ServiceProject',
    props:{
      headtext: String,
      msg: String
    }
  }

</script>