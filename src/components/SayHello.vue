<template>
  <div>
    <q-avatar>
      <img src="@/assets/images/robert small.png" />
    </q-avatar>
    {{ name }} sagt: Hallo!
  </div>
</template>

<script setup>
defineProps({
  name: String,
});
</script>
