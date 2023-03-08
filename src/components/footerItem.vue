<template>
    <div class="footer-item">
        <img :src="img" alt="">
        <p>{{text}}</p>
    </div>
</template>

<script>
export default {
    name: "footerItem",
    props:{
        img: String,
        text: String
    }
}
</script>