<template>
  <div class="v-main-wrapper">
    <keep-alive>
      <router-view></router-view>
    </keep-alive>
    <p>{{title}}</p>
  </div>
</template>
<script>
import { mapGetters } from "vuex";

export default {
  name: "v-main-wrapper",

  props: {},
  data() {
    return {
      title: ""
    };
  },
  computed: {},
  methods: {},
  watch: {},
  mounted() {}
};
</script>
<style>
.v-main-wrapper {
  max-width: 900px;
  margin: 0 auto;
}
</style>