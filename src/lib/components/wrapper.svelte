<script lang="ts">
	let { children, class: className = '' } = $props();
</script>

<div class={['mx-auto w-[1024px]', className]}>
	{@render children()}
</div>
