<template>
  <nav class="navbar fixed-top row navbar-expand-lg shadow pb-0">
    <router-link
      class="navbar-brand font-pacifico ml-2 text-white"
      :to="{ name: 'home' }"
      style="font-size: 1.5rem"
    >N e x u s</router-link>

    <div class="col-7 ml-0 p-0">
      <form class="form-inline d-flex justify-content-left md-form form-sm ml-1">
        <!-- <i class="fas fa-search" aria-hidden="true"></i> -->
        <input
          class="input p-0 form-control form-control w-100 bg-transparent"
          type="text"
          placeholder="  Search ..."
          aria-label="Search"/>
      </form>
    </div>

    <div class="col-1 justify-content-end p-0">
      <img
        class="mail ml-5"
        style="height:2.3rem;"
        src="https://img.icons8.com/ios/50/000000/important-mail.png"/>
      <img
        class="notify ml-4"
        style="height:2.2rem;"
        src="https://img.icons8.com/small/32/000000/appointment-reminders--v1.png"/>
    </div>

    <div class="col-3 p-0 ml-4 justify-content-end d-flex">
      <p class="pt-3 text-white">Justin Goss</p>
      <img
        class="ml-3"
        style="height:3rem;"
        src="https://img.icons8.com/ios-glyphs/40/000000/user--v1.png"/>
    </div>

    <button
      class="navbar-toggler border-0"
      type="button"
      data-toggle="collapse"
      data-target="#navbarText"
      aria-controls="navbarText"
      aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <!-- <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item" :class="{ active: $route.name == 'home' }">
          <router-link :to="{ name: 'home' }" class="nav-link">Home</router-link>
        </li>
        <li
          class="nav-item"
          v-if="$auth.isAuthenticated"
          :class="{ active: $route.name == 'profile' }"
        >
          <router-link class="nav-link" :to="{ name: 'profile' }">Profile</router-link>
        </li>
      </ul>
      <span class="navbar-text">
        <button class="btn btn-success" @click="login" v-if="!$auth.isAuthenticated">Login</button>
        <button class="btn btn-danger" @click="logout" v-else>logout</button>
      </span>
    </div>-->
  </nav>
</template>


<script>
export default {
  name: "Navbar",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
.navbar {
  background-color: #1d1e30;
}

/* .mail{
    : aliceblue;
} */
</style>