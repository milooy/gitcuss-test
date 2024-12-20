<script setup lang="ts">
import { useData } from 'vitepress'

const { title } = useData()
</script>

<template>
  <div :key="title" class="giscus">
    <component
      :is="'script'"
      src="https://giscus.app/client.js"
      data-repo="milooy/gitcuss-test"
      data-repo-id="R_kgDONgF71A"
      data-category="Announcements"
      data-category-id="DIC_kwDONgF71M4ClYlK"
      data-mapping="pathname"
      data-strict="0"
      data-reactions-enabled="1"
      data-emit-metadata="0"
      data-input-position="bottom"
      data-theme="preferred_color_scheme"
      data-lang="ko"
      crossorigin="anonymous"
      data-loading="lazy"
      async
    />
  </div>
</template>