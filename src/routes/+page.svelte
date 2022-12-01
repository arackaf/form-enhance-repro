<script>
  import { enhance } from "$app/forms";

  function enhanceFn(arg) {}
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<!-- Comment out the use:enhance={enhanceFn} to make this work -->
<form use:enhance={enhanceFn}>
  Type in me and hit enter <input name="search" />
</form>
