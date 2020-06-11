<template>
  <div>
    <div class="pt-16 pb-20 px-4 sm:px-6 lg:pt-24 lg:pb-28 lg:px-8">
      <div class="max-w-3xl mx-auto">
        <div>
          <h1
            class="text-3xl leading-9 tracking-tight font-medium text-gray-900 sm:text-4xl sm:leading-10"
          >My 100 days of code pledge!</h1>
          <p
            class="mt-3 text-xl leading-7 text-gray-500 sm:mt-4"
          >To make learning more fun, I've started doing 100 days of code from April-2020.</p>
          <p
            class="mt-3 text-xl leading-7 text-gray-500 sm:mt-4"
          >I strongly believe that transparency is the key of greater success, that is why I've started this pledge publically.</p>

          <all-tweets />
        </div>
      </div>
    </div>
    <about-me-section />
    <hobbies />
  </div>
</template>

<script>
import { Tweet } from 'vue-tweet-embed'
import tweetIds from '~/static/tweets.json'
export default {
  components: {
    Tweet
  },
  asyncData ({ params }) {
    return { tweetIds }
  }
}
</script>
