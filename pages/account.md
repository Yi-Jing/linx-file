<div class="flex flex-col justify-center items-center w-full h-full relative">
  <h1 class="title">那麼，有誰可以操作這些功能？</h1>
</div>

---
transition: fade-out
---

<div class="flex justify-center items-center relative">
  <img class="w-full" src="images/account/01.png">
  <Mark type="circle" :at="1" width="80" height="40" top="48" right="20" />
</div>

---
transition: fade-out
---

<div class="flex justify-center items-center relative">
  <img class="w-1/2" src="images/account/02.png">
</div>
<v-click>
  <Mark type="underline" :at="1" width="400" height="40" top="200" left="300" />
</v-click>
<div class="absolute top-40 left-10">
  <ul>
    <v-click><li>平台管理者</li></v-click>
    <v-click><li>一般職員</li></v-click>
    <v-click><li>組長</li></v-click>
    <v-click><li>主管</li></v-click> 
  </ul>
  <v-click><div class="mt-2">不同角色會有不同的操作權限</div></v-click>
</div>
