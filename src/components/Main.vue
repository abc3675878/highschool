<template lang="pug">
  //- Vue 的背景圖要寫行內只能用 v-bind style 讀取 public 的圖片
  //- 要讀 src 要寫在 css
  #main(:style="{backgroundImage: 'url(./images/0101.jpg)'}")
    img(src="@/0104.jpg")
    br
    br
    p 
      | 國立科技高中
      br
      | 國立科技高中國立科技高中
      br
      | 國立科技高中國立科技高中
      br
      | 國立科技高中國立科技高中
      br
      | 國立科技高中國立科技高中
</template>

<script>
export default {
  name: 'Main',
}
</script>
