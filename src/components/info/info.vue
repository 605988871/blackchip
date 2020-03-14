<template>
  <b-card class="info">
    <b-container class="bv-example-row">
      <b-row class="text-center">
        <b-col cols="8" style="padding:0 0">
          <div class="left-col">
            <div class="data">
              <span style="font-size:16px">更新日期：</span>
              <span style="font-size:13px">2020年3月13日</span>
            </div>
            <div class="total-revenue">
              <span class="left-tr">0.00%</span>
              <span class="right-tr">总收益</span>
            </div>
            <div class="date">
              <b-container class="bv-example-row">
                <b-row class="text-center">
                  <b-col>
                    <p>周</p>
                    <p>0.00%</p>
                  </b-col>
                  <b-col>
                    <p>月</p>
                    <p>0.00%</p>
                  </b-col>
                  <b-col>
                    <p>最新净值</p>
                    <p>0.00%</p>
                  </b-col>
                  <b-col>
                    <p>总资产</p>
                    <p>10000000.0</p>
                  </b-col>
                </b-row>
              </b-container>
            </div>
          </div>
        </b-col>
        <b-col>
          <div class="right-col">
            <p class="username">
              Domi
            </p>
            <p>
              加入时间:2020.03.16
            </p>
            <p>
              持有份额:0.333
            </p>
            <p>
              初始净值:90.22
            </p>
          </div>
        </b-col>
      </b-row>
    </b-container>
  </b-card>
</template>

<script>
export default {
  name: "",
  props: {},
  date: {}
};
</script>

<style lang="scss">
@import './index.scss'
</style>