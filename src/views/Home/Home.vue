<template>
  <div class="wrapper">
    <search :isSearching="false" @click.native="changeToSearch"></search>
    <div class="tab">
    </div>
    <mt-tab-container v-model="selected" swipeable>
      <mt-tab-container-item id="2">
        <classic/>
      </mt-tab-container-item>
    </mt-tab-container>
  </div>
</template>

<script>
  import classic from "@/views/Home/classic";
  import expert from "@/views/Home/expert";
  import major from "@/views/Home/major";
  import recommend from "@/views/Home/recommend";
  import search from "@/components/search";
  export default {
    components: {
      classic,
      expert,
      major,
      recommend,
      search
    },
    data() {
      return {
        selected: "2",
      }
    },
    mounted() {},
    methods: {
      changeToSearch() {
        this.$router.push({
          path: 'home/search'
        });
      }
    }
  };
</script>

<style lang="stylus" scoped>
.wrapper
  width 100%
  height 92%
  .mint-search
      height initial
  .mint-navbar .mint-tab-item.is-selected
    margin 0
</style>
