<template>
	<section class="text-block">
		<div class="text-block__content">
			<h2 class="text-block__title">Welcome to Our Place</h2>
			<h3 class="text-block__subtitle">
				At Our Place, we believe in the power of home-cooking to bring
				people together. Our collections are new heirlooms from the
				cultures and places that make up the fabric of the modern
				multi-ethnic kitchen. We design thoughtfully, source ethically,
				and produce sustainably because what we make is connected to one
				another and the earth we share.
			</h3>
		</div>
	</section>
</template>

<script setup></script>

<style lang="scss" scoped>
.text-block {
	padding: 120px 135px;
	&__content {
		display: flex;
		align-items: center;
		justify-content: center;
		gap: 135px;
		background-color: $white;
	}
	&__title {
		max-width: 400px;
		width: 100%;
		font-size: 46.2px;
		line-height: 1;
		letter-spacing: 1.25px;
		font-weight: 700;
		text-align: center;
	}
	&__subtitle {
		font-size: 16px;
		line-height: 25.9px;
		font-weight: 400;
		color: $gray;
	}
}
</style>
