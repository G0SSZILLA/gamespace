<template>
  <div class="Home">
    <!-- NOTE search and header -->
    <header class="row">
      <!-- NOTE Search Bar -->
      <div class="col-7">
        <form class="form-inline d-flex justify-content-center md-form form-sm mt-0">
          <i class="fas fa-search" aria-hidden="true"></i>
          <input
            class="form-control form-control-sm ml-3 w-75"
            type="text"
            placeholder="Search"
            aria-label="Search"/>
        </form>
      </div>

      <div class="col-1"></div>
      <div class="col-1"></div>
      <div class="col-1"></div>
      <div class="col-2"></div>
    </header>
  </div>
</template>


<script>
export default {
  name: "Home",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
</style>
