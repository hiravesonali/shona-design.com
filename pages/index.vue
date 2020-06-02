<template>
  <div>
    <hero />
    <design-work title="My recent work" :designs="designs" />
    <about-me-section />
    <hobbies />
  </div>
</template>

<script>
import designs from '~/static/home-designs.json'
export default {
  asyncData ({ params }) {
    return { designs }
  }
};
</script>
