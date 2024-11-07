---
descripton: A beginner's guide to getting started with Vue 3.
image: /image/logo.png
head:
  meta:
    - name: 'og:image'
  content: /image/logo.png
publishedAt: 2023-08-03 20:15:00
toc: true
---

# Introduction to Vue 3

![Vue 3 Introduction](/image/logo.png)

## What is Vue 3?

Vue.js 3 us a progressive JavaScript framework for building user interfaces on the web. It's designed to be incrementally adoptable can easily scale between a library and a full-featured framework

---

## Why Choose Vue 3?

Vue 3 comes with several exciting features that make it an excellent choice for developers:

**Composition API:** This new API provides a set of additive, function-based APIs that allow flexible composition of component logic.

**Faster rendering:** Vue 3 featured a faster virtual DOM and improved runtime performance.

**Improved TypeScript support:** Vue 3's codebase is written in TypeScript, allowing for better TypeScript integration.

---

## Getting Started with Vue 3

Here's basic Vue 3 application setup:

```javascript
const { createApp } = Vue;
const app = createApp({
  data() {
    return {
      message: 'Hello Vue 3!',
    };
  },
});
app.mount('#app');
```
