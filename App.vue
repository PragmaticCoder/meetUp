<template>
  <view class="container">
    <Hello />
  </view>
</template>

<script>
import Hello from "./src/components/Hello";

export default {
  components: {
    Hello
  },
  data() {
    return {
      title: "SHHH Confessions"
    };
  }
};
</script>

<style>
.container {
  background-color: white;
  align-items: center;
  justify-content: center;
  flex: 1;
}
</style>
