<template>
<div>
  <USStocks/>
</div>
</template>

<script>
import USStocks from "../components/USStocks";
import EUStocks from "../components/EUStocks";
export default {
  name: "Home",
  components: {EUStocks, USStocks}
}
</script>

<style scoped>

</style>