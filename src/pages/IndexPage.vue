<template>
  <q-page>
    <div class="column flex-center">
      <div class="text-h1 text-primary q-mt-xl text-weight-medium">
        Divya Kundra
      </div>
      <div class="text-h4 text-secondary q-mt-md q-mb-xl text-weight-regular">
        FrontEnd Developer
      </div>
      <ExpansionItems></ExpansionItems>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import ExpansionItems from "src/components/ExpansionItems.vue";

export default defineComponent({
  name: "IndexPage",

  components: {
    ExpansionItems,
  },
});
</script>
