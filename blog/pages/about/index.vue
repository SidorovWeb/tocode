<template>
  <div class="wrapper-content wrapper-content--fixed">
    <section class="about">
      <div class="container">
        <h1 class="title">About my blog</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium tenetur impedit ipsum est dolore enim, reprehenderit vero recusandae ea. Sapiente, quia magnam. Accusamus reiciendis, quis officia eligendi saepe optio necessitatibus!</p>
        <Intro title="Lorem ipsum do" />
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium tenetur impedit ipsum est dolore enim, reprehenderit vero recusandae ea. Sapiente, quia magnam. Accusamus reiciendis, quis officia eligendi saepe optio necessitatibus!</p>
        <img src="@/assets/img/about.jpeg" alt="">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium tenetur impedit ipsum est dolore enim, reprehenderit vero recusandae ea. Sapiente, quia magnam. Accusamus reiciendis, quis officia eligendi saepe optio necessitatibus!</p>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  head () {
    let title = 'About My Blog Page !',
      descr = 'About My SSR Blog! Wich Nuxt.js',
      type = 'site'

    return {
      title: title,
      meta: [
        { hid: 'og:title', name: 'og:title', content: title },
        { hid: 'description', name: 'description', content: descr },
        { hid: 'og:description', name: 'og:description', content: descr },
        { hid: 'og:type', name: 'og:type', content: type }
      ]
    }
  }
}
</script>


<style lang="scss">
.about {
  text-align: center;
  p {
    margin-bottom: 10px;
  }
}
</style>
