<script>
  import Header from "./header.svelte";
</script>

<nav>
  <Header />
</nav>
<slot />

<style>
  :global(body) {
    margin: 0;
  }
  :global(p, h1, h2, h3) {
    font-family: "Montserrat", sans-serif;
  }
</style>
