<template>
  <q-page padding>
    <q-markdown :src="mdPrivacy" />
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
