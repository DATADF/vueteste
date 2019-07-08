<template>
    <div id="home">
        <Services mensagem="Meu primeiro componente Vue.js"/>
    </div>
</template>


<script>
import Services  from "./components/Services";

export default {
    name: 'home',
    components: {
        Services
    }
}
</script>
