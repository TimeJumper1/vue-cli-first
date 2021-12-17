<template>
    <div class="image">
      <img src="../assets/img/01.png" alt="">
    </div>
</template>

<script>
export default {
  name: "hero",
  props: {
    msg: String,
  },
};
</script>
<style scoped >
.image{
    width: 100%;
    height: auto;
    margin: auto;
    border: 1px solid blue;
    border-radius: 30px;
}
</style>