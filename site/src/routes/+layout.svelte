<script>
  import Layout from '../components/Theme/Layout.svelte';
</script>

<Layout>
  <slot></slot>
</Layout>

<style>
  :global(body) {
    margin: 0;
    font-family: Arial, sans-serif;
  }
</style>
