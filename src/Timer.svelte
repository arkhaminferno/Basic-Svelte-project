<script>
  import ProgressBar from "./progressBar.svelte";
</script>

<style>
  h2 {
    margin: 0;
  }
  .start {
    width: 100%;
    background-color: crimson;
    color: white;
  }
</style>

<div bp="grid">
  <h2 bp="offset-5@md 4@md 12@sm">
    Seconds left:

    <h2 />
  </h2>
</div>

<ProgressBar />

<button class="start">Start</button>
