<template>
  <div class="relative bg-gray-50 pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8">
    <div class="relative max-w-7xl mx-auto">
      <div class="text-center">
        <h2
          class="text-3xl leading-9 tracking-tight font-extrabold text-gray-900 sm:text-4xl sm:leading-10"
        >My recent work</h2>
        <p class="mt-3 max-w-2xl mx-auto text-xl leading-7 text-gray-500 sm:mt-4">
          I've worked on logo design, brand design, corporate identity kit, web and mobile application design.
          <br />I use
          <a href="https://procreate.art" target="_blank" class="text-indigo-600">ProCreate</a> on my iPad to create beautiful illustrations.
          <br />
        </p>
      </div>

      <div class="mt-12 grid gap-5 max-w-lg mx-auto lg:grid-cols-3 lg:max-w-none">
        <design-card v-for="design in designs" :key="design.key" v-bind:design="design" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      designs: [
        {
          title: 'Floral background',
          description: 'My first attempt to make a floral Background!',
          image: "floral.jpeg"
        },
        {
          title: 'Floral background',
          description: 'My second attempt to make a floral Background!',
          image: "floral2.jpeg"
        },
        {
          title: 'Monstera background',
          description: 'Hand-drawn colorful monstera background in Procreate!',
          image: "monstera.jpeg"
        },
        {
          title: 'Seafloor',
          description: 'Where the sea meets Land!',
          image: "seafloor.jpeg"
        },
        {
          title: 'Human Sculpture',
          description: 'Imagination has no limits!',
          image: "human-sculpture.jpeg"
        },
        {
          title: 'Mountains and Lake',
          description: 'The first try to make a simple nature background!',
          image: "mountains-lake.jpeg"
        },
        {
          title: 'Social Distancing Illustration',
          description: 'Social Distancing Illustration',
          image: "social-distancing.JPG"
        },
        {
          title: 'Snow Mountains',
          description: 'Snow Mountains',
          image: "mountains.JPG"
        },
        {
          title: 'Social Distancing',
          description: 'Social Distancing',
          image: "nature.JPG"
        }
      ],
    };
  }
};
</script>
