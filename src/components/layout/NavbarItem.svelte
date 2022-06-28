<script>
  import Box from "./core/Box.svelte";

  export let label = "";
</script>

<div class="button">
  <Box m="10px">
    {label}
  </Box>
</div>

<style>
  .button {
    background-color: cadetblue;
  }
  .button:hover {
    background-color: burlywood;
  }
</style>
