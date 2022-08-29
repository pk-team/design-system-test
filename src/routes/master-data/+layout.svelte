<script lang="ts">
  import Nav from "./[slug]/nav.svelte";
</script>

<div class="split">
  <Nav />
  <div>
    <slot />
  </div>
</div>

<style>
  .split {
    display: grid;
    grid-template-columns: 250px 1fr;
  }

  
</style>
