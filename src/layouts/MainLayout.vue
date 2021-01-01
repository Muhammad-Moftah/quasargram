<template>
   <q-layout view="lHh Lpr lFf">
      <q-header>
         <q-toolbar>
            <q-toolbar-title class="text-center">Quasar App</q-toolbar-title>
         </q-toolbar>
      </q-header>
      <q-footer class="bg-white" bordered>
         <q-tabs class="text-grey-10" active-color="primary">
            <q-route-tab icon="eva-home" to="/" />
            <q-route-tab icon="eva-camera" to="/" />
         </q-tabs>
      </q-footer>

      <q-page-container>
         <router-view />
      </q-page-container>
   </q-layout>
</template>

<script>
export default {
   name: "MainLayout",
   components: {},
   data() {
      return {
         leftDrawerOpen: false,
      };
   },
};
</script>
