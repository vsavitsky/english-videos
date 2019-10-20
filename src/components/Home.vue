<template>
  <div>
    <video-details/>
  </div>
</template>

<script>
import VideoDetails from '@/components/VideoDetails'
export default {
  name: 'Home',
  components: {
    VideoDetails
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
