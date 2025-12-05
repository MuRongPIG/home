<template>
  <div class="more-content">
    <span class="greeting">
      你好，我是@MuRongPIG，一名cs专业本科生。<br>
      生长于江汉平原，现于九河下梢求学。<br>
      你能找到这里并看到这段话，说明我们有缘分，不是吗？<br>
      欢迎通过下面以及右边的相关链接了解我、联系我。<br>
    </span>
  </div>
</template>

<script setup lang="ts">
import { ref, h } from 'vue';
import { Error } from "@icon-park/vue-next";
import { mainStore } from "@/store";

const store = mainStore();
</script>

<style lang="scss" scoped>
.more-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  margin-top: 20px;
  width: 100%;
  max-height: 100%;
  flex: 1;

  .greeting {
    font-family: MiSans VF;
    font-weight: 520;
    font-size: 1.05rem;
    width: 100%;
    text-align: center;
    padding: 0 10px;
    color: var(--text-color);
  }

}
</style>

