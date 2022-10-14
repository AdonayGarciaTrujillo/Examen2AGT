<template>
    <div class="row">
        <div class="col-12 col-md-3">
            <h1>Formularios.agt</h1>

        </div>
        <div class="col-12 col-md-6">
            <img :src="url" :alt="alt" width="100">
        </div>
    </div>
    <hr>
</template>

<script>
    export default {
        data: () => ({
            url: "https://cdn.svgporn.com/logos/vue.svg",
            alt: "Vue.js",
        }),
    };
</script>