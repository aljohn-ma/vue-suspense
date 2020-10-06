<template>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>

<script>
function asyncSetTimeout(timeout) {
  return new Promise(resolve => setTimeout(resolve, timeout));
}

export default {
  async setup() {
    await asyncSetTimeout(10000);
    console.log("success");
  }
};
</script>

<style></style>
