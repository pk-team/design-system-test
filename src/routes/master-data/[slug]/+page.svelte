<script lang="ts">
    import { page } from '$app/stores'
    
</script>

<div class="layout">
    <h1>{$page.params.slug}</h1>
</div>


<style>
    .layout {
        padding: 1rem;
    }
</style>