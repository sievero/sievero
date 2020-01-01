<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="bg-blue-grey-10">
      <q-toolbar>
        <q-btn flat no-caps label="sievero" size="lg" to="/" />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-blue-grey-10">
      <q-btn no-caps flat to="/privacy" label="Privacy" />
    </q-footer>
  </q-layout>
</template>

<script>
export default {
  name: 'MyLayout'
};
</script>
