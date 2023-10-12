<template>
   
  <div :class="type">
      <!-- {{title}} -->
      <p class="title">{{ title }}</p>
  </div>
</template>

<script>

export default {
  props: {
      title: String,
      type: String //primary, danger, warning, success
  }
}

</script>

<style scoped>
.regular {
  background-color: #2686e7;
  border-color: #06386a;
}
.angry {
  background-color: #e72636;
  border-color: #6a0609;
}
.sad {
  background-color: #7D7C7C;
  border-color: #7D7C7C;
}
.happy {
  background-color: #fdfa72;
  border-color: #fdfa72;
}
div {
  padding: 10px;

  border-radius: 4px;
  
  margin: 8px 0;
  text-align: center;
}
.regM {
  background-color: #2686e7;
  border-color: #06386a;
  width: 434px;
  height: 150px;
}
.hapM {
 background-color: #7D7C7C;
  border-color: #7D7C7C;
  width: 434px;
  height: 150px;
}
.sadM {
  background-color: #fdfa72;
  border-color: #fdfa72;
  width: 434px;
  height: 150px;
}
.angM {
  background-color: #e72636;
  border-color: #6a0609;
  width: 434px;
  height: 150px;
}

</style>