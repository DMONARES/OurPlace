<template>
	<section class="hero">
		<div class="hero__content">
			<h3 class="hero__subtitle">Meet The Always Pan</h3>
			<h1 class="hero__title">
				Your new <br />
				<span>skillet</span>
			</h1>
			<UiButton class="hero__button"> Shop the Always Pan </UiButton>
		</div>
	</section>
</template>

<script setup></script>

<style lang="scss" scoped>
.hero {
	padding: 170px 0;
	background: url("~/public/img/hero-bg.png") no-repeat center center;
	background-size: cover;

	&__content {
		margin-left: 380px;
		display: flex;
		flex-direction: column;
		align-items: start;
		gap: 9px;
	}
	&__subtitle {
		text-transform: uppercase;
		font-size: 16px;
		font-weight: 400;
		line-height: 16px;
		color: $black;
	}
	&__title {
		margin-bottom: 48px;
		font-size: 50px;
		font-weight: 400;
		line-height: 72px;
		letter-spacing: 1px;
		color: $black;
		span {
			text-decoration: underline;
		}
	}
}
</style>
