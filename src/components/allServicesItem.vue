<template>
    <div class="all-services__item">
        <img src="../assets/img/all-services.png" alt="">
        <h3><span>{{number}}</span>{{title}}</h3>
        <p>{{info}}</p>

        <a href="#">Подробнее</a>
    </div>
</template>

<script>
    export default {
        name: 'projectComp',
        props:{
            number: String,
            title: String,
            info: String
        }
    }
</script>