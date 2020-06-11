<template>
  <div>
    <div v-for="tweetId in tweetIds" :key="tweetId">
      <!--frist row-->
      <div class="flex flex-no-wrap lg:flex-row flex-row-reverse justify-center pt-10">
        <!-- left col -->
        <div class="w-2/5 sm:2/3 flex-none p-2">
          <div class="text-gray-700 lg:float-right float-left border-2 rounded border-green-200 bg-green-200 shadow-lg px-2">
            <Tweet id="1260913733687279616" />
          </div>
        </div>
        <!--line column-->
        <div class="w-1/5 sm:1/3 flex-none float-left">
          <div class="bg-indigo-400 p-1 h-full w-1 mx-auto">
            <button
              class="h-24 w-24 mt-56 bg-indigo-400 hover:bg-indigo-600 text-white font-bold rounded-full -ml-12"
            >Day #1</button>
          </div>
        </div>
        <!--right column-->
        <div class="w-2/5 flex-none p-2 hidden lg:block"></div>
      </div>

      <div class="flex flex-no-wrap sm:flex-row-reverse1 justify-center">
        <!-- left col -->
        <div class="w-2/5 sm:2/3 flex-none p-2 hidden lg:block"></div>
        <!--line column-->
        <div class="w-1/5 sm:1/3 flex-none float-left">
          <div class="bg-indigo-400 p-1 h-full w-1 mx-auto">
            <button
              class="h-24 w-24 mt-56 bg-indigo-400 hover:bg-indigo-600 text-white font-bold rounded-full -ml-12"
            >Day #1</button>
          </div>
        </div>
        <!--right column-->
        <div class="w-2/5 flex-none p-2">
          <div class="text-gray-700 float-left border-2 rounded border-green-200 bg-green-200 shadow-lg px-2">
            <Tweet id="1260913733687279616" />
          </div>
        </div>
      </div>
    </div>
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
