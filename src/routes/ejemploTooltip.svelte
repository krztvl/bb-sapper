<script>
  import { onMount } from "svelte";

  onMount(() => {
    var tooltipTriggerList = [].slice.call(
      document.querySelectorAll('[data-toggle="tooltip"]')
    );
    var tooltipList = tooltipTriggerList.map(function(tooltipTriggerEl) {
      return new bootstrap.Tooltip(tooltipTriggerEl);
    });
  });
</script>

<svelte:head>
  <title>About</title>
</svelte:head>

<h1>Ejemplo de implemetacíon de elementojs boosttap</h1>

<button
  type="button"
  class="btn btn-secondary"
  data-toggle="tooltip"
  data-placement="top"
  title="Tooltip on top">
  Tooltip on top
</button>
<button
  type="button"
  class="btn btn-secondary"
  data-toggle="tooltip"
  data-placement="right"
  title="Tooltip on right">
  Tooltip on right
</button>
<button
  type="button"
  class="btn btn-secondary"
  data-toggle="tooltip"
  data-placement="bottom"
  title="Tooltip on bottom">
  Tooltip on bottom
</button>
<button
  type="button"
  class="btn btn-secondary"
  data-toggle="tooltip"
  data-placement="left"
  title="Tooltip on left">
  Tooltip on left
</button>
