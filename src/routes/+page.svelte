<script>
  let title = "Gaming guides";
  const updateTitle = () => {
    title = "new title";
  };
</script>

<div class="home">
  <nav>
    <a href="/">home</a>
    <a href="/about">about</a>
    <a href="/guides">guides</a>
  </nav>
  <h2>{title}</h2>
  <p>
    Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illo aperiam
    deleniti quia minima dolorem iste rem. Rerum, possimus a? Porro rerum
    necessitatibus facere autem! Tempora eaque repellat molestias maiores
    voluptatem?
  </p>
  <button on:click={updateTitle}>Click me</button>
  <input type="text" bind:value={title} />
  <a href="/guides">View guides</a>
  <a href="/about">About us</a>
  <a href="/guides">Guides</a>
</div>

<style>
  .home {
    text-align: center;
    display: block;
    margin: 20 px, auto;
  }
</style>
