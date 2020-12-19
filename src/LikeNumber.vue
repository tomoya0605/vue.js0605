<template>
  <p>いいね({{ number }})</p>
  <botton @click="increment">+1</botton>
</template>

<script>
export default {
  data: function() {
    return {
      number:5
    };
  },
  methods: {
    increment() {
      this.number +=1;
    }
  }
};
</script>
