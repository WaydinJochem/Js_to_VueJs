<template>
    <router-link :to="{ name: 'Product', params: { id: product.id } }">
        <img :src="product.image" :alt="product.name">
        <h3>
            {{ product.title }}
        </h3>
        <p>Description: {{ product.desc }}</p>
        <p>Price: $ {{ product.price }}</p>
    </router-link>
</template>
<script>
export default {
    props: ["product"]
}
</script>
