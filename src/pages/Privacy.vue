<template>
  <q-page padding>
    <div class="row justify-center">
      <div class="col-md-8">
        <q-markdown :src="mdPrivacy" />
      </div>
    </div>
  </q-page>
</template>

<script>
import mdPrivacy from '../markdown/privacy.md';

export default {
  data() {
    return {
      mdPrivacy
    };
  }
};
</script>
