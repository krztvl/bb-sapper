<script>
  import Nav from "../components/Nav.svelte";
  import Header from "../components/Header.svelte";
  export let segment;
</script>

<style>
  :global(.btn-bellabike) {
    background-color: rgb(237, 111, 26);
    color: white;
  }
</style>

<Header {segment} />
<main>
  <slot />
</main>
