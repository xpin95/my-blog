<template>
    <div>
        <nav-top>
        </nav-top>
        <article-preview>
        </article-preview>
    </div>
</template>

<script>
    import NavTop from '@/components/NavTop.vue'
    import ArticlePreview from '@/components/ArticlePreview.vue'


    export default {
  name: 'MainComponent',
        components: {
            NavTop,
            ArticlePreview
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1{
    color:red;
}
</style>
