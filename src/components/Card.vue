<script>
export default {
    props: {
		thumb: String,
		price: String,
		series: String,
		type: String,
	},

}
</script>



<template>
  <div class="card">
    <img :src="thumb" alt="series">
    <h4>{{ series.toUpperCase() }} </h4>
</div>
</template>



<style lang="scss" scoped>
@use './../assets/styles/partials/variables' as *;

.card{
    height: 150px;
    width: 150px;
    margin-top: 4em;
    img{
        max-height: 100%;
        aspect-ratio: 1/1;
        box-shadow: 5px 10px rgb(36, 36, 36);
    } 
    h4{
        margin-top: 1em;
        color: $base-color;
    }
}

</style>