<script lang="ts">
  import Header from "$lib/header.svelte";

  import "../styles/app.css";
</script>

<Header>Header1</Header>

<div class="wrap">
  <slot />
</div>

<style>
</style>
