<script>
  export let title = "Ninja Gaming"
</script>

<div class="navbar">
  <div class="left">
    <a href="/">
      <img src="/favicon.png" alt="site logo" />
    </a>
    <a href="/">
      <h1>{title}</h1>
    </a>
  </div>
  <div class="list">
    <ul>
      <li>
        <a href="/">Home</a>
        <a href="/guides">Guides</a>
        <a href="/about">About</a>
      </li>
    </ul>
  </div>
</div>

<style>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.5rem 1rem;
  }
  .left {
    display: flex;
    gap: 1rem;
  }
  img {
    max-height: 60px;
  }
</style>
