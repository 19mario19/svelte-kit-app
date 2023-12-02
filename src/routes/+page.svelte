<script lang="ts">
  import Navbar from "$lib/Navbar.svelte"

  let title: string = "Ninja Gaming Guides"

  let input: string = ""
  function updateTitle(input: string): void {
    title = input || "No title"
  }
</script>

<div class="index">
  <h2>{title ? title : "Some title"}</h2>
  <input type="text" bind:value={input} />
  <button on:click={() => updateTitle(input)}>Update title</button>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit quod
    accusantium aspernatur error harum, quisquam optio qui. Neque, ratione
    cupiditate?
  </p>
</div>

<style>
  .index {
    display: flex;
    flex-direction: column;
    text-align: center;
    margin: 3rem auto;
  }

  button {
    max-width: 200px;
    margin: 0 auto;
  }
  input {
    max-width: 300px;
    margin: 1rem auto;
  }
</style>
