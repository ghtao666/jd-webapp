<template>
  <div class="count-down">
    <div class="number van-hairline--surround">{{hour}}</div>
    <div class="colon">:</div>
    <div class="number van-hairline--surround">{{min}}</div>
    <div class="colon">:</div>
    <div class="number van-hairline--surround">{{second}}</div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      time: "01-00-39",
      hour: "",
      min: "",
      second: ""
    };
  },
  created() {
    this.hour = this.time.split("-")[0].padStart(2, "0");
    this.min = this.time.split("-")[1].padStart(2, "0");
    this.second = this.time.split("-")[2].padStart(2, "0");

    setInterval(() => {
      this.second = (this.second - 1 + "").padStart(2, "0");
      if (this.second === "-1") {
        this.second = "59";
        this.min = (this.min - 1 + "").padStart(2, "0");
        if (this.min === "-1") {
          this.min = "59";
          this.hour = (this.hour - 1 + "").padStart(2, "0");
          if (this.hour === "-1") {
            this.hour = "00";
            this.min = "00";
            this.second = "00";
          }
        }
      }
    }, 1000);
  }
};
</script>

<style lang="less">
.count-down {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  font-size: 12px;
  margin-left: 5px;
  .number {
    height: 20px;
    line-height: 20px;
    padding-left: 2px;
    padding-right: 2px;
  }
  .colon{

  }
}
</style>
