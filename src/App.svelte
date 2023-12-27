<script>
  import Counter from './lib/Counter.svelte'
</script>

<main class="mainDiv">
  <h1>ROHAN</h1>

  <div class="card">
    <Counter />
  </div>



  <!-- why are they using the anchor tag rather then link tag... -->
  <!-- <p>
    Check out <a href="https://github.com/sveltejs/kit#readme" target="_blank" rel="noreferrer">SvelteKit</a>, the official Svelte app framework powered by Vite!
  </p> -->

</main>

<style>
  .mainDiv {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    height: 580px;
  }


</style>
