<template>
  <div class="hello">
    <navbar></navbar>
    <div style="height: 6rem;"></div>
    <info></info>
    <div style="height: 3rem;"></div>
    <card msg="A股"></card>
    <div style="height: 3rem;"></div>
    <card msg="B股"></card>
    <div style="height: 3rem;"></div>
    <card
      msg="美股"
      content="因涉及其他所有权剥离，暂不公示。实际持仓和操作参考："
      linkName="Johnny不会玩美股ZH130860"
      link="https://xueqiu.com/P/ZH130860"
    ></card>
    <div style="height: 3rem;"></div>
    <card
      msg="数字货币"
      content="根据管理规定，暂时对一般投资人保密。"
    ></card>
  </div>
</template>

<script>
import navbar from "./navbar/navbar.vue";
import info from "./info/info.vue";
import card from "./card/card.vue";
export default {
  name: "HelloWorld",
  components: {
    navbar,
    info,
    card
  },
  props: {},
  mounted() {
    document
      .querySelector("body")
      .setAttribute("style", "background-color:#eee;padding:0 30px");
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body {
}
</style>
