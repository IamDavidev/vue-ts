<template>
  <div class="ts">
    <h2>
      {{ title }}
    </h2>
    <h3>
      {{ personaEnTypeScrip }}
    </h3>
  </div>
</template>
<script lang="ts">
import { defineComponent, ref } from "vue";
import { Persona } from "../interfaces/Interface";
export default defineComponent({
  setup() {
    const title = ref<String>("esto es un title con TypeScript");
    console.log(title);
    const personaEnTypeScrip = ref<Persona>({
      nombre: "David",
      apellifo: "lezama",
      edad: 18,
      programadorJR: false,
    });
    console.log(personaEnTypeScrip);

    return { title, personaEnTypeScrip };
  },
});
</script>
<style scoped></style>
