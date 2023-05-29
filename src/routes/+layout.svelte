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
</style>
