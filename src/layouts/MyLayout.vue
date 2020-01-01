<template>
  <q-layout view="lhh Lpr lff">
    <q-header class="bg-blue-grey-9">
      <q-toolbar class="row">
        <div class="col-1">
          <q-btn flat no-caps label="sievero" size="lg" to="/" />
        </div>
        <q-space />
        <div class="col-1">
          <q-btn flat no-caps label="Sign up" to="/" />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer class="bg-blue-grey-9">
      <div class="q-pa-md">
        <div class="row justify-around">
          <div class="col-2">
            <div class="text-h6">Links</div>
            <q-btn
              no-caps
              class="text-blue-grey-3"
              flat
              to="/privacy"
              label="Privacy"
            />
          </div>
          <div class="col-2">
            <div class="text-h6">Follow Us</div>
            <q-btn
              round
              flat
              icon="eva-github"
              type="a"
              href="https://github.com/sievero"
              target="_blank"
            />
            <div class="text-body2">&copy; 2019 - 2020, Sievero LLC</div>
          </div>
        </div>
      </div>
    </q-footer>
  </q-layout>
</template>

<script>
export default {
  name: 'MyLayout'
};
</script>
