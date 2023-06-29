<template>
    <div v-if="product" class="tutorial-details">
        <img :src="product.image" :alt="product.name">
        <div>
            <h3>
                {{ product.name }}
            </h3>
            <p>Description: {{ product.desc }}</p>
            <p>Rating: $ {{ product.price }}</p>
        </div>
    </div>
</template>
<script>
export default {
    props: ["id"],
    computed: {

        product() {
            return this.$store.state.product;
        },
    },
    mounted() {
        this.$store.dispatch("getProduct", this.id)   
    }
}
</script>
<style></style>