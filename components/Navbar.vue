<template>
  <div>
  <b-navbar toggleable="lg" variant="white" class="shadow-sm p-2 mb-6 bg-body rounded">
    <b-navbar-brand href="/" class=""><span class="brand_we">We</span><span class="brand_carpark">Carpark</span></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="/">Home</b-nav-item>
        <b-nav-item href="test">Download</b-nav-item>
      </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>
</template>

<script>
export default {

}
</script>

<style>

.brand_we{
    color: #fd9509;
    font-size: 20px;
}

.brand_carpark{
    color: #11833a;    
    font-size: 20px;
}


</style>