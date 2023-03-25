<template>
  <v-carousel height="1000px">
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
      reverse-transition="fade-transition"
      transition="fade-transition"
    >
      <!--<v-img height="50%" width="50%" eager />-->
    </v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          src: '..//сертификат основы верстки.png'
        },
        {
          src: '..//сертификат js.jpg'
        },
        {
          src: '..//сертификат фрайм.png'
        },
        {
          src: '..//сертификат линукс.png'
        },
        {
          src: '..//сертификат англ..png'
        },
        {
          src: '..//сертификат методологии.png'
        }
      ]
    }
  }
}
</script>
