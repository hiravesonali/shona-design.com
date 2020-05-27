<template>
  <div class="flex flex-col rounded-lg shadow-lg overflow-hidden">
    <a href="https://shona-design.com/designs/monstera-background" title="Monstera background">
      <div class="flex-shrink-0">
        <img
          class="h-auto w-full object-cover"
          :src="require('~/assets/images/designs/'+design.image)"
          :alt="design.title"
        />
      </div>
    </a>
  </div>
</template>

<script>
export default {
  props: ['design'],
}
</script>
