<template>
  <div class="example">
    <v-date-picker v-model="date" :select-attribute="selectAttribute" is-inline></v-date-picker>
  </div>
</template>

<script>
export default {
  data() {
    return {
      date: new Date(),
      selectAttribute: {
        popover: {
          visibility: 'visible',
        },
      },
    };
  },
};
</script>

