<template>
  <view>
    <text class="text-color-primary">{{ message }}</text>
    <button :title="btnText" />
  </view>
</template>

<script>
export default {
  data() {
    return {
      message: "Welcome to SHHH Confessions",
      btnText: "Post"
    };
  }
};
</script>

<style>
.text-color-primary {
  color: blue;
}
</style>
