<template>
    <div class="container">
        <h2>{{ mensagem }}</h2>
    </div>
</template>

<script>
export default {
    name:'Services',
    props: {
    mensagem: String
  }
}
</script>

<style scoped>
    .container {
        width: 100%;
        max-width: 960px;
        margin: auto;
    }

    h2 {
        color: orangered;
    }
</style>

