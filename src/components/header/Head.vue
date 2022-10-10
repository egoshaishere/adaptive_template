<template>
  <div class="head">
    <div class="head_box">
      <div class="big">WANTED</div>
      <div class="smal">hired or dead</div>
      
    
    </div>
  </div>
</template>

<script>
export default {
  name: "Head"
}
</script>

<style scoped>
@import url('http://fonts.cdnfonts.com/css/grand-duke');
/* @import '../../styles/head.css'; */
.head_box {
  font-family: 'GRAND DUKE', sans-serif;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.smal {
    font-size: 40px;
    /* color: brown; */
}
.big {
    font-size: 80px;
    /* color: brown; */
}
</style>