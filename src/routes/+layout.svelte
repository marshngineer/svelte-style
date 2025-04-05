<script lang="ts">
	import Wrapper from '$lib/components/wrapper.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<Wrapper>
	{@render children()}
</Wrapper>
