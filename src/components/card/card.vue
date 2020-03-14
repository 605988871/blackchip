<template>
  <div class="cards">
    <h5>{{this.msg}}</h5>
    <div class="content" v-if="this.content">
      {{this.content}}<a :href="this.link" v-if="this.linkName&&this.link">{{this.linkName}}</a>
    </div>
  </div>
</template>

<script type='text/ecmascript-6'>

  export default {
    name:'',
    props:{
      msg:String,
      content:String,
      linkName:String,
      link: String
    },
    data () {
      return {

      };
    },

    components: {},

    computed: {},

    watch: {},

    beforeMount() {},

    mounted() {},

    methods: {}

  }

</script>
<style lang='scss'>
.cards{
  border:2px solid #cf4338 !important;
  text-align: left;
  padding:20px;
  h5{
    font-weight: 800;
    display: inline-block;
    margin:0px;
  }
  .content{
    padding:20px 0;
    font-size: 20px;
    a{
      font-size: 14px;
    }
  }
}
</style>