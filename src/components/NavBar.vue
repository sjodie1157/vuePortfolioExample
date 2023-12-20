<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <img src="https://drive.google.com/uc?id=144xcMWgRenQCxKQBtSCNVXZeDeJy886S" alt="logo">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarText">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <router-link to="/" class="nav-link">Home</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/about" class="nav-link">About</router-link> 
            </li>
            <li class="nav-item">
              <router-link to="/project" class="nav-link">Project</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/resume" class="nav-link">Resume</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/testimonial" class="nav-link">Testimonials</router-link>
            </li>
            <li class="nav-item">
              <router-link to="/contact" class="nav-link">Contact</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
</template>

<script>
    export default {
    name: 'NavBarComp',
        
    }
</script>

<style scoped>

</style>