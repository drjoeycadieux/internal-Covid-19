<template>
  <div>
    <img
      width="100"
      height="100"
      src="https://covidtracker-coronavirus.netlify.app/assets/logo.png"
    />
  </div>
</template>

<script>
export default {
  props: {
    width: {
      type: Number,
      default: 90,
    },
    height: {
      type: Number,
      default: 90,
    },
  },
};
</script>
