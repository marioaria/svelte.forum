<script lang="ts">
  import '$lib/assets/main.css';
  import favicon from '$lib/assets/favicon.svg';

  let { children } = $props();
</script>

<svelte:head>
  <link rel="icon" href={favicon} />
  <title>Svelte Forum</title>
</svelte:head>

{@render children()}
