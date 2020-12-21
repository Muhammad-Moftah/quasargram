<template>
   <q-layout view="lHh Lpr lFf">
      <q-header bordered class="">
         <q-toolbar>
            <q-toolbar-title class="text-center"> Quasar App </q-toolbar-title>
         </q-toolbar>
      </q-header>

      <q-footer bordered>
         <q-tabs>
            <q-router-tab> test </q-router-tab>
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
