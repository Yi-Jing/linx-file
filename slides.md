---
# You can also start simply with 'default'
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cdn.jsdelivr.net/gh/slidevjs/slidev-covers@main/static/6terqWC_KCk.webp
# some information about your slides (markdown enabled)
title: Linx 導覽
info: Linx 行銷自動化系統導覽
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
fonts:
  sans: Robot
  serif: Robot Slab
  mono: Fira Code
mdc: true
---

<div class="flex flex-col justify-center items-center w-full relative">
  <img class="w-[180px] mb-4" src="/images/logo.svg"/>
  <h1>行銷自動化系統</h1>
</div>

---
src: pages/introduction.md
---

---
transition: fade-out
src: pages/material.md
---

---
transition: fade-out
src: pages/segment.md
---

---
transition: fade-out
src: pages/story.md
---

---
transition: fade-out
src: pages/account.md
---

---
transition: fade-out
src: pages/about.md
---

---
layout: center
class: text-center
---

<div>
  <div class="w-full h-full absolute bg-[#000000e8] top-0 left-0">
    <div class="flex flex-col items-center justify-center h-full text-center">
      <img class="w-[180px] mb-4" src="/images/logo.svg"/>
      <h1 style="color: white">讓系統為您發送行銷廣告</h1>
    </div>  
  </div>
</div>

<style>
@import "./styles.css";
</style>