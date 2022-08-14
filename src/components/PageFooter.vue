<script setup lang="ts">
import { NGrid, NGridItem, NP, NH3 } from 'naive-ui';
</script>

<template>
  <n-grid :x-gap="12" :y-gap="30" :cols="2">
    <n-grid-item>
      <n-h3>About us</n-h3>
      <n-p
        >Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum suscipit laborum vero autem
        pariatur ipsum explicabo a consectetur, veniam magni? Doloremque molestiae possimus
        doloribus, soluta officiis numquam asperiores fuga laborum?</n-p
      >
    </n-grid-item>
    <n-grid-item class="author">
      <n-h3>Author</n-h3>
      <img src="/ljanner.png" alt="Icon of ljanner" />
      <span>ljanner</span>
    </n-grid-item>
    <n-grid-item span="2">
      <n-p class="copyright">Copyright &copy; 2022 All rights reserved | Janner.dev</n-p>
    </n-grid-item>
  </n-grid>
</template>

<style scoped>
.n-grid {
  padding: 20px 5rem;
  background-color: #f6f6f6;
}
.author span {
  margin-left: 5px;
}
.author img {
  vertical-align: middle;
  width: 30px;
  border-radius: 15%;
}
.copyright {
  text-align: center;
}
</style>
