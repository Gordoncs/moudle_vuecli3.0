<template>
  <div>4</div>
</template>

<script>
import { getTableData } from "@/api/data";
export default {
  name: "Nav",
  mounted() {
    getTableData("人员信息").then(res => {
      console.log(res);
    });
  }
};
</script>

<style scoped></style>
