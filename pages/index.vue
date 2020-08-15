<template>
  <div class="container">
    <div>
      <div class="welcome">
        <p>欢迎来到我的站点</p>
        <p>我是一名使用PHP和GO的后端工程师</p>
        <p>这里用来练习前端</p>
      </div>
      <div class="contact">
        <p>这里才刚刚开始，你可以在下面这些地方找到我：</p>
        <p><a href="https://github.com/panxianhai">Github</a></p>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.welcome {
  font-size: large;
}
.contact {
  margin-top: 1rem;
}
</style>
