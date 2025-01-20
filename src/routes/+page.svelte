<script>
  let num = $state(0);
</script>

<h1>Welcome to Test123</h1>
<p>
  Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
  documentation
</p>
<button
  class="b-lg"
  onclick={() => {
    num += 1;
  }}>+</button
>
<span>{num}</span>
<button
  class="b-lg"
  onclick={() => {
    num -= 1;
  }}>-</button
>

<style>
  .b-lg {
    width: 3em;
    height: 3em;
    font-size: 1em;
  }
</style>
