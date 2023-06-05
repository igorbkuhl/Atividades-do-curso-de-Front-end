<template>
  <div class="about">
    <h1>Esta é a página sobre este projeto.</h1>
    <RedButton text="Contato" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import RedButton from "@/components/RedButton.vue";

export default defineComponent({
  name: "AboutView",
  components: {
    RedButton
  }
});
</script>