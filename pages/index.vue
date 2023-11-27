<!-- <template>
  <div>
    Hello from the main page!
  </div>
</template>

<script setup>
  useSeoMeta({
    title: 'Main Page',
    description: 'This is the main page',
    ogTitle: 'Main Page',
    ogDescription: '[og:description]',
    ogImage: '[og:image]',
    ogUrl: '[og:url]',
    twitterTitle: 'Main Page',
    twitterDescription: 'This is the main page',
    twitterImage: '[twitter:image]',
    twitterCard: 'summary'
  });
</script> -->

<template>
  <article class="prose dark:prose-invert prose-h1:text-2xl max-w-none">
    <ContentDoc path="/" />
  </article>
</template>

<script setup lang="ts">
  useHead({
    title: 'Projects',
  });
</script>
