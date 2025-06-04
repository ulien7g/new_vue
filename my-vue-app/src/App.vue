<template>
<HeaderComponent title="title"/>
<MessageComponent title="Привіт, Vue!" message="Я вмію створювати компоненти із пропсами"/>
</template>

<script>
import HeaderComponent from "./components/Header.vue";
import MessageComponent from "./components/MessageComponent.vue"

export default {
  components: {
    HeaderComponent,
    MessageComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
