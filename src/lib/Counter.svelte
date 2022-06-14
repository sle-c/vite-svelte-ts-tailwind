<script lang="ts">
  let count: number = 0;
  const increment = () => {
    count += 1;
  };
</script>

<button
  on:click={increment}
  class="px-5 py-3 text-white bg-red-500 border-solid shadow-md hover:bg-red-600 focus:ring-1 focus:outline-none focus:ring-opacity-30"
>
  Clicks: {count}
</button>
