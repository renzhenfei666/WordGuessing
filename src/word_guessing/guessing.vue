<template>
  <div class="container">
    <div class="page">
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>

      <div class="list">{{ dataList[0] }}</div>

      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
      <div class="list">{{ dataList[0] }}</div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      dataList: [
        "恒星",
        "象牙",
        "老板娘",
        "血",
        "指挥家",
        "汽油",
        "假期",
        "夹克",
        "技师",
        "天才",
        "鞋",
        "射线",
        "绳子",
        "盲点",
        "罗宾汉",
        "飞鸟",
        "显微镜",
        "坑",
        "垃圾桶",
        "浆果",
        "寺庙",
        "痕迹",
        "鹰",
        "喷射",
        "自行车",
        "企鹅",
        "书签",
        "遗体",
        "恶作剧",
        "易拉罐",
      ],
    };
  },
};
</script>

<style scoped>
.container {
  width: 100%;
  height: 100%;
  padding: 50px;
}
.page {
  display: flex;
  justify-content: space-between;
  height: calc(100% - 100px);
  width: calc(100% - 100px);
  flex-wrap: wrap;
}
.list {
  height: calc(100% / 5 - 20px);
  width: calc(100% / 5 - 20px);
  border-radius: 10px;
  background-color: #cad5eb;
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
