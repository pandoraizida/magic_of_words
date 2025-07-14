<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="main_block">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      You’ve successfully created a project!!
    </h3>
  </div>
</template>

<style scoped>
.main_block {
  border-style: dotted;
  border-color: blueviolet;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

/* .greetings h1,
.greetings h3 {
  text-align: center;
} */

</style>
