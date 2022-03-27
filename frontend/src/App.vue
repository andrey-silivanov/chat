<template>

  <div class="container-scroller">
    <right-block/>
    <div class="container-fluid page-body-wrapper">
      <top-block/>
      <main-block/>
    </div>
    <!-- page-body-wrapper ends -->
  </div>
</template>

<script>
import RightBlock from "@/components/RightBlock";
import TopBlock from "@/components/TopBlock";
import MainBlock from "@/components/MainBlock";

export default {
  name: 'App',
  components: {
    RightBlock,
    TopBlock,
    MainBlock
  }
}
</script>
