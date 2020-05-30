<template>
    <div>
        <header >
            <video playsinline="playsinline" muted  autoplay loop src="https://aurorachristianschool.com/storage/acsv.mp4"></video>
        </header>

        <main>
            <div class="jumbotron text-center">
                <h1 class="display-4 ">
                    Train up a child in the way he should go, <br />
                    And when he is old he will not depart from it.</h1>
                <hr class="my-4">
                <i>- Proverbs 22:6</i>
            </div>
        </main>
    <div class="container">
        <h2 class="display-4" >
        </h2>
    </div>


    </div>
</template>

<script>
  export default {
    data() {
      return {
        slide: 0,
        sliding: null
      }
    },
    methods: {
      onSlideStart(slide) {
        this.sliding = true
      },
      onSlideEnd(slide) {
        this.sliding = false
      }
    }
  }
</script>
