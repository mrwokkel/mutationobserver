<script>
  // import { dev } from '$app/env';
  // import { onMount } from 'svelte';
  import 'virtual:windi.css';
  import 'virtual:windi-devtools';

  // This does work...
  // dev && onMount(async () => {
  //   (await import('virtual:windi-devtools')).default;
  // });
</script>

<slot></slot>