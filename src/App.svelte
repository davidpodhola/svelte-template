<script>
  import "./main.css";

  import Page from "./stories/Page.svelte";
</script>

<!-- App.svelte -->
<style lang="scss">
  :global(body) {
    font-family: Arial, Helvetica, sans-serif;
    font-size: 5rem;
    height: 100vh;
    display: flex;
    @apply bg-red-200;
  }
</style>

<Page />
