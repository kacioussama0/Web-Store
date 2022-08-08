<template>

  <div class="card shadow border-1 border-dark rounded">

    <div class="card-header bg-white border-0 py-3 text-center">
      <slot name="header" />
    </div>

    <div class="card-body">

      <slot name="body"/>

    </div>

    <div class="card-footer bg-white border-0 ">
      <slot name="footer"/>
    </div>

  </div>


</template>

<script>
export default {



}
</script>

<style scoped>



</style>