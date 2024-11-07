<template>
  <div>
    <article class="prose dark:prose-invert prose-h1:text-2xl max-w-none">
      <ContentDoc path="/about" />
    </article>

    <div>
      <button @click="enableCustomLayout">Update Layout</button>
    </div>
  </div>
</template>

<script setup>
// definePageMeta({
//   layout: 'another',
// });

function enableCustomLayout() {
  setPageLayout('another');
}
</script>
