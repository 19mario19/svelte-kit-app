<script>
  import Navbar from "$lib/Navbar.svelte"
</script>

<header>
  <Navbar />
</header>
<main>
  <slot />
</main>
<footer>
  <p>Copyright 2023 Mario</p>
</footer>

<style>
  footer {
    text-align: center;
  }
</style>
