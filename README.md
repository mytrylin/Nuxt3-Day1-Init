# NUXT3 - Day1 - 建立專案

### 專案建立指令

```
npx nuxi init [project name]
```

 npx nuxi init Nuxt3-Day1

### 加入目錄及頁面

```
npx nuxi add <template> <name>
```
npx nuxi add page index

### 使用 \<NuxtPage\>

```html
<!-- app.vue -->
<template>
  <NuxtRouteAnnouncer />
  <!-- <NuxtWelcome /> -->
  <NuxtPage />
</template>
```
