<template>
	<div class="banner">
		<div class="banner__content">
			<p>
				Shipping and returns are always free from our place to yours 🙂
			</p>
		</div>
	</div>
</template>

<script setup></script>

<style lang="scss" scoped>
.banner {
	padding: 10px 0;
	background-color: $primary;
	&__content {
		text-align: center;

		p {
			text-transform: uppercase;
			color: $brown;
			font-size: 12px;
			line-height: 20.4px;
			letter-spacing: .5px;
		}
	}
}
</style>
