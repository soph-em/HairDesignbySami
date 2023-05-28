<script>
  import Header from "./header.svelte";
</script>

<Header />
<slot />

<style>
  :global(body) {
    margin: 0;
  }
</style>
