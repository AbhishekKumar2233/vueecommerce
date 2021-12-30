<template>
  <div>
    <VmProductsList></VmProductsList>
  </div>
</template>

<script>
import VmProductsList from "@/components/products_list/ProductsListContainer";

export default {
  name: "index",
  components: {
    VmProductsList,
  },
};
</script>
