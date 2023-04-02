<template>
    <!-- custom navbar -->
    <div>
        <nav class=" container-fluid navbar navbar-expand-lg bg-warning shadow p-4">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><strong>TheEcome</strong> </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarScroll">
      <ul class="navbar-nav m-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
        <li class="nav-item">
          <a class="nav-link" href="/index">home</a>
          <NuxtLink to="/index" class="nav-link">Home</NuxtLink>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/About">About</a>
          <NuxtLink to="/About" class="nav-link">About Us</NuxtLink>
        </li>
        <li class="nav-item dropdown">
          <NuxtLink to="/services" class="nav-link">Services</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/contact" class="nav-link">Contact Us</NuxtLink>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
    </div>
</template>






<script>
export default {
    name:'AppHeader',
}
</script>

<style lang="scss" scoped>

</style>