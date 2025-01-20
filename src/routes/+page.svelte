<script>
  let num = $state(0);
</script>

<h1>Welcome to <span class="name">Test123</span></h1>
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
  .name {
    color: red;
    font-size: 1.5em;
  }
  
  .b-lg {
    width: 3em;
    height: 3em;
    font-size: 1em;
  }
</style>
