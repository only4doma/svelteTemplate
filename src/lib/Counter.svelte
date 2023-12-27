<script>
  let count = 0
  const increment = () => {
    count += 1
  }

  const decrement = () => {
    count -= 1
  }
</script>

<div class="showCount">
  <button on:click={decrement}>
    -
  </button>
  
  <div class="count">
    {count}
  </div>
  
  <button on:click={increment}>
    +
  </button>
</div>

<style>
  .showCount {
    display: flex;
    gap: 10px;
  }
</style>