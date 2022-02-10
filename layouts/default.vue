<template>
  <div>
    <delay-hydration>
      <div>
        <Nuxt />
      </div>
    </delay-hydration>
  </div>
</template>
<script>
import { DelayHydration } from "nuxt-delay-hydration/dist/components";
export default {
  components: {
    DelayHydration,
  },
};
</script>