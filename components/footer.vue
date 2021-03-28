<template>
  <div class="warapper">
    <footer>
      <p class="copyright">Copyright©︎ 2021 加本真大 All Rights Reserved.</p>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.warapper {
  min-height: 20vh;
  position: relative;
  padding-bottom: 60px;
  box-sizing: border-box;
}
footer {
  background-color: #2b4257;
  width: 100%;
  color: white;
  display: flex;
  justify-content: flex-end;
  font-weight: bold;
  font-size: 13px;
  padding: 10px;
  position: absolute;
  bottom: 0;
}
@media screen and (max-width: 400px) {
  footer {
    font-size: 10px;
  }
}
</style>