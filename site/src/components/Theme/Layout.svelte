<script>
  import Header from './Header.svelte';
  import Footer from './Footer.svelte';

  export let title = "My Svelte Site";
</script>

<Header {title} />
<main>
  <slot></slot>
</main>
<Footer />

<style>
  main {
    padding: 1rem;
  }
</style>

