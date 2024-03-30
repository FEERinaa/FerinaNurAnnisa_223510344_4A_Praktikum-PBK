<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h4>
      Halo Guys!<br />
      Saya adalah seorang wanita independen. Wanita independen yang lebih mengutamakan pekerjaan
      dibandingkan kegiatan yang kurang bermanfaat.<br />
      Uang memang bukan segalanya, tapi segalanya butuh uang. Oleh karena itu, jika ada suatu
      kegiatan yang menghasilkan uang yang halal, Jangan lupa untuk mengajak saya.<br />
      Karena saya adalah orang yang bertanggungjawab atas tugas yang berikan.Selain itu, saya
      berkepribadian yang jujur, ramah, dapat dipercaya, dan dapat memimpin ataupun dipimpin.
      <!-- <a href="https://vitejs.dev/" target="_blank" rel="noopener">Vite</a> + -->
      <!-- <a href="https://vuejs.org/" target="_blank" rel="noopener">Vue 3</a>. -->
    </h4>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  position: relative;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
