<template>
  <q-page class="flex flex-center">
    <vue-audio :file="path"></vue-audio>
  </q-page>
</template>

<style>
</style>

<script>
import boot from 'bootstrap-css'
import VueAudio from 'vue-audio'
export default {
  name: 'PageIndex',
  components: {
    VueAudio, boot
  },
  data () {
    return {
      path: './statics/musica.mp3'
    }
  },
  methods: {
  }
}
</script>
