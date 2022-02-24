<template>
  <h2>{{title}}</h2>
  <h3>{{likes}}</h3>
</template>
<script>
export default {
  props: {
    title: {
      type: String,
      default: "페이지 제목입니다."
    },
    likes:{
      type: Number,
      
    }
  }
}
</script>