<template>
  <section class="section">
    <div class="container yokoponzoo-container">
      <figure class="image is-128x128 yokoponzoo-top-image">
        <img class="is-rounded" src="../../static/test.jpg">
      </figure>
      <br>
      <h1 class="title yokoponzoo-my-name">Koki Yokoyama</h1>
      <div class="columns is-mobile yokoponzoo-media-content">
        <div class="column">
          <a href="https://www.facebook.com/yokoponzoo"><img src="../../static/media-icon/facebook500.png" alt="" class="image is-64x64 yokoponzoo-media-icon"></a>
        </div>
        <div class="column">
          <a href="https://www.instagram.com/0601ykgram/"><img src="../../static/media-icon/instagram.png" alt="" class="image is-64x64 yokoponzoo-media-icon"></a>
        </div>
        <div class="column">
          <a href="https://note.mu/yokoponzoo"><img src="../../static/media-icon/note.png" alt="" class="image is-64x64 yokoponzoo-media-icon"></a>
        </div>
        <div class="column">
          <a href="https://github.com/yokoponzoo"><img src="../../static/media-icon/github.png" alt="" class="image is-64x64 yokoponzoo-media-icon"></a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Main',
  data () {
    return {
    }
  }
}
</script>

<style scoped>
.yokoponzoo-container {
  max-width: 750px;
}
.yokoponzoo-top-image {
  margin: auto;
}
.yokoponzoo-my-name {
  text-align: center;
}
.yokoponzoo-media-content {
  max-width: 450px;
  margin: auto;
}
.yokoponzoo-media-icon {
  margin: auto;
}
</style>
