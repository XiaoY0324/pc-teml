<template>
  <div class="wrap">
    <div class="box">
      tesstteststststst
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {};
  },
  methods: {
    e() {}
  },
  created() {
    console.log(`home page loaded`);
  }
};
</script>
<style scoped lang="scss">
.wrap {
  height: 100vh;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  .box {
    img {
      width: 520px;
      height: 268px;
    }
    p {
      font-size: 18px;
      font-family: PingFangSC-Regular, PingFang SC;
      font-weight: 400;
      color: rgba(153, 153, 153, 1);
      line-height: 25px;
      text-align: center;
    }
  }
}
</style>
