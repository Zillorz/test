<script>
  let num = $state(0);
</script>

<h1>Welcome to Test123</h1>
<p>
  Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the
  documentation
</p>
<button
  onclick={() => {
    num += 1;
  }}>+</button
>
<span>{num}</span>
<button
  onclick={() => {
    num -= 1;
  }}>-</button
>
