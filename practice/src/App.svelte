<h1>
  My first Svelte component
</h1>

<button on:click={increment}>
  Hello {name}, count {count}
</button>

<a href="https://youtube.com">Link to my youtube</a>
<Component />
<style>
  h1{
    color: rebeccapurple;
  }
  button {
    font-size: 44px;
  }
</style>

<script>
  import Component from "./lib/Component.svelte";


  let name = 'Prince';
  console.log(name);
  let count = 0;
  function increment() {
    count++;
  }
</script>