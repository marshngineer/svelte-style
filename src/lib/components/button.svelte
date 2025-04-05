<script lang="ts">
	import { Button } from 'bits-ui';

	let { children } = $props();
</script>

<Button.Root
	class="bg-dark text-background shadow-mini hover:bg-dark/95 inline-flex items-center justify-center rounded-full
      px-6 py-1 font-semibold active:scale-[0.98] active:transition-all"
>
	{@render children()}
</Button.Root>
