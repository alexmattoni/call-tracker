<script lang="ts">
    import type { LayoutData } from './$types';
</script>

<svelte:head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
</svelte:head>

<nav class="navbar navbar-expand-lg bg-dark navbar-dark mb-4 px-4">
        <a class="navbar-brand" href="/">Call Tracker</a>
        <div class="container justify-content-end">
            <a class="btn btn-outline-success me-3 my-2" type="button" href="/">home</a>
            <a class="btn btn-outline-danger" type="button" href="/tracking">tracking</a>
        </div>
</nav>

<slot></slot>