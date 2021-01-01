<template>
   <q-page class="flex column flex-center">
      <div v-if="$q.platform.is.desktop">I'm only rendered on desktop!</div>

      <div v-if="$q.platform.is.mobile">I'm only rendered on mobile!</div>
      <div v-if="$q.platform.has.touch">I'm have touch</div>
      <div v-if="!$q.platform.has.touch">I'm have no touch</div>
   </q-page>
</template>

<script>
export default {
   name: "PageIndex",
};
</script>
