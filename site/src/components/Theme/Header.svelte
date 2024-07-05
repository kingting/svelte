<script>
  export let title = "My Svelte Site";
</script>

<header>
  <h1>{title}</h1>
  <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
    <a href="/blog">Blog</a>
  </nav>
</header>

<style>
  header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
  }
  nav a {
    margin: 0 1rem;
    color: #fff;
    text-decoration: none;
  }
</style>

