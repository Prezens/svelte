<script>
	export let foo;
</script>

<p>before</p>
{#if foo}
	<p>foo!</p>
{/if}
<p>after</p>