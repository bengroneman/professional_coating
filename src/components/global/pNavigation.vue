<template>
  <div>
    <b-navbar toggleable="lg" type="dark" variant="secondary" fixed="top">
      <b-navbar-brand href="#">Professional Coating</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <div class="mr-1 mr-left text-black">
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="m1-auto">
            <b-nav-item href="#home">Home</b-nav-item>
            <b-nav-item href="#services">Services</b-nav-item>
            <b-nav-item href="#contact">Contact Us</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: 'pnavigation'
}
</script>

