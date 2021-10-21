<template>
  <div class="row main-header">
    <div class="col content">
      <div class="left-header">
        ridhi
      </div>
      <div class="right-header">
        naka
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
.main-header {
  height: 100px;
}

.content {
  display: flex;
}

.left-header {
  display: flex;
  flex: 50%;
}

.right-header {
  display: flex;
  flex: 50%;
}
</style>
