<template>
  <view>
    <text class="text-color-primary">{{ message }}</text>
    <button :title="btnText" :on-press="handleClick" />
  </view>
</template>

<script>
export default {
  data() {
    return {
      message: "Welcome to SHHH Confessions",
      btnText: "Post"
    };
  },
  methods: {
    handleClick() {
      alert("Testing Button Click");
    }
  }
};
</script>

<style>
.text-color-primary {
  color: blue;
}
</style>
