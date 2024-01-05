<template>
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      aaa: [
        {
          bbb: {
          },
        },
      ],
    };
  },
  mounted() {
    const index = 0
    this.aaa[index].bbb.ccc = 1;
    console.log(this.aaa[index].bbb.ccc);
  },
};
</script>
