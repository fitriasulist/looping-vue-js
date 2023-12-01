<template>
    <div>
      <h1>List angka 1 sampai 50</h1>
      <ul>
        <li v-for="number in numbers" :key="number">{{ number }}</li>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        numbers: [],
      };
    },
    created() {
      this.generateNumbers();
    },
    methods: {
      generateNumbers() {
        for (let i = 1; i <= 50; i++) {
          this.numbers.push(i);
        }
      },
    },
  };
  </script>
  