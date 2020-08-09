<script>
  import Nav from "../components/Nav.svelte";
  import Header from "../components/Header.svelte";
  export let segment;
</script>

<style>
  main {
    padding: 0 auto;
    margin: 0 auto;
  }
</style>

<Header {segment} />
<main>
  <slot />
</main>
