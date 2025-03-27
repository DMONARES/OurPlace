<script setup>
	const props = defineProps({
		disabled: Boolean,
	});
</script>

<template>
	<button
		class="ui-button"
		:disabled="disabled"
	>
		<slot />
	</button>
</template>

<style lang='scss'>
	.ui-button
	{
		// base styles
		cursor: pointer;
		border: none;
		padding: 20px 40px;
		border: 1px solid transparent;
		border-radius: 0;
		background-color: $accent;
		color: $white;
		font-size: 12px;
		text-transform: uppercase;
		font-weight: 700;
		line-height: 20.4px;
		letter-spacing: .5px;
		transition: .3s;

		// effects
		&:disabled
		{
			pointer-events: none;
			opacity: .7;
		}
		&:hover { opacity: .8; }
	}
</style>