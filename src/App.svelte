<script>
  export let name;
  let asd = 123;
  function click() {
    asd++;
  }
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!{asd}</h1>
<button on:click={click} />
