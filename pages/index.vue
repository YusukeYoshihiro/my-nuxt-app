<template>
  <section class="container">
    <nuxt-link 
      v-for="post in posts"
      :key="post.id"
      :to="post.id">
      <article class="post-preview">
        <div class="post-preview"></div>
      </article>
    </nuxt-link>
  </section>
</template>
<script>
export default {
  data() {
    return {
      posts: [
        {
          title: "Boys be anbisious",
          previewText: "This will be awesome, dont＼’t　miss it!",
          thumbnaiUrl: "",
          id: "boys-be-anbisious",
        },
        {
          title: "Girls be married",
          previewText: "This will be awesome, dont＼’t　miss it!",
          thumbnaiUrl: "",
          id: "girls-be-married",
        },
      ],
    };
  },
};
</script>

<style></style>
