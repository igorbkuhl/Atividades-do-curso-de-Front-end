
<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br />
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
        >vue-cli documentation</a
      >.
    </p>
    <h3>Instituto Evoluir</h3>
    <RedButton text="Entrar" />
    <RedButton text="Cadastrar" />
    <RedButton text="Sair" />
  </div>
</template>

<script lang="ts">
/* eslint-disable */
import { defineComponent } from "vue";
import RedButton from "@/components/RedButton.vue";

export default defineComponent({
  name: "HelloWorld",
  props: {
    msg: String,
  },
  components: {
    RedButton
  }
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #b94279;
}
</style>
