<script>
  import Title from "$lib/title.svelte";
</script>

<header>
  <Title title="Gaming Guides" />
</header>

<slot />
<footer>
  <p>Copyright 2023 Giulia GmbH</p>
</footer>

<style>
  header {
    display: flex;
    justify-content: center;
  }
  main {
    max-width: 960px;
    margin: 20px auto;
  }
  footer {
    text-align: center;
  }
</style>
