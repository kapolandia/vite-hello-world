<script>
    export default {
        name: 'AppHeader',
        name: 'AppJumbotron'
}
</script>

<template>
<nav style="background-color: aquamarine;" >
  <div class="container-fluid">
    <a class="navbar-brand" href="#">
      <img src="../assets/vue.svg" alt="Logo" width="30" height="24" class="d-inline-block align-text-top">
      <span class="title-text">Hello Vite</span>
    </a>
  </div>
</nav>
</template>

<style>
    .container-fluid{
        max-width: 700px;
        margin: 0 auto;
        padding: 20px;
    }
    .navbar-brand{
        display: flex;
        align-items: center;
    }
    .navbar-brand img{
        margin-right: 10px;
    }
    .title-text{
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        font-size: 20px;
        font-weight: 700;
        text-decoration: solid;
        color: #000;
    }

</style>