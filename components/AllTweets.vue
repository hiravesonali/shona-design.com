<template>
  <div class="">
    <!--frist row-->

    <div class="flex flex-no-wrap lg:flex-row flex-row-reverse justify-center pt-10">
      <!-- left col -->
      <div class="w-2/5 sm:2/3 flex-none p-2">
        <div class="text-gray-700 lg:float-right float-left border-2 rounded border-green-200 bg-green-200 shadow-lg px-2">
          <blockquote class="twitter-tweet">
            <p lang="en" dir="ltr">
              Day 10 of the challenge
              <a
                href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw"
              >#100DaysOfCode</a>
              <br />Today, I&#39;ve learned php composer, how I can use it. Also, I&#39;ve made a simple working backend for twitter application. No backend framework, pure PHP &amp; Tailwindcss so far.
              <br />[10/100]😺
              <a
                href="https://twitter.com/hashtag/WomenWhoCode?src=hash&amp;ref_src=twsrc%5Etfw"
              >#WomenWhoCode</a>
              <a
                href="https://twitter.com/hashtag/CodeNewbie?src=hash&amp;ref_src=twsrc%5Etfw"
              >#CodeNewbie</a>
              <a href="https://t.co/aIIYO464gf">pic.twitter.com/aIIYO464gf</a>
            </p>&mdash; Sonali Hirave (@ShonaDesign)
            <a
              href="https://twitter.com/ShonaDesign/status/1260913733687279616?ref_src=twsrc%5Etfw"
            >May 14, 2020</a>
          </blockquote>
          <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
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
          <blockquote class="twitter-tweet">
            <p lang="en" dir="ltr">
              Day 10 of the challenge
              <a
                href="https://twitter.com/hashtag/100DaysOfCode?src=hash&amp;ref_src=twsrc%5Etfw"
              >#100DaysOfCode</a>
              <br />Today, I&#39;ve learned php composer, how I can use it. Also, I&#39;ve made a simple working backend for twitter application. No backend framework, pure PHP &amp; Tailwindcss so far.
              <br />[10/100]😺
              <a
                href="https://twitter.com/hashtag/WomenWhoCode?src=hash&amp;ref_src=twsrc%5Etfw"
              >#WomenWhoCode</a>
              <a
                href="https://twitter.com/hashtag/CodeNewbie?src=hash&amp;ref_src=twsrc%5Etfw"
              >#CodeNewbie</a>
              <a href="https://t.co/aIIYO464gf">pic.twitter.com/aIIYO464gf</a>
            </p>&mdash; Sonali Hirave (@ShonaDesign)
            <a
              href="https://twitter.com/ShonaDesign/status/1260913733687279616?ref_src=twsrc%5Etfw"
            >May 14, 2020</a>
          </blockquote>
          <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
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
