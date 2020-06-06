<template>
    <div>

        <footer>

            <b-container class="text-white">
                <b-row>
                    <b-col>
                        #38 Zamora Street<br />
                        Buag, Bambang<br />
                        Nueva Vizcaya 3702<br />
                    </b-col>

                    <b-col>
                        <b-icon icon="phone" ></b-icon>
                            +63 78 803 1354<br />
                        <b-icon icon="envelope" ></b-icon>
                            hi@aurorachristianschool.com<br />
                    </b-col>
                </b-row>
            </b-container>
        </footer>
    </div>
</template>

<script>
import { BIcon, BIconPhone, BIconEnvelope } from 'bootstrap-vue'
  export default {
    components: {
        BIcon,
        BIconPhone,
        BIconEnvelope
    },
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

<style scoped>
    footer {
        padding-top: 100px;
        padding-bottom: 100px;
    }
</style>
