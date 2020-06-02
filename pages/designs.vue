<template>
  <div>
    <design-work title="My design work" :designs="designs" />
  </div>
</template>


<script>
import designs from '~/static/all-designs.json'
export default {
  asyncData ({ params }) {
    return { designs }
  }
};
</script>
