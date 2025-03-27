<template>
	<section class="partners">
		<div class="partners__content">
			<h2 class="partners__title">
				"Doing the job of eight traditional cookware pieces"
			</h2>
			<ul class="partners__list">
				<li class="partners__item">
					<img
						src="~/public/img/bon-appetit.png"
						alt="bon-appetit"
						class="partners__img"
					/>
				</li>
				<li class="partners__item">
					<img
						src="~/public/img/new-york.png"
						alt="new-york"
						class="partners__img"
					/>
				</li>
				<li class="partners__item">
					<img
						src="~/public/img/vogue.png"
						alt="vogue"
						class="partners__img"
					/>
				</li>
				<li class="partners__item">
					<img
						src="~/public/img/the-ophar.png"
						alt="the-ophar"
						class="partners__img"
					/>
				</li>
			</ul>
		</div>
	</section>
</template>

<script setup></script>

<style lang="scss" scoped>
.partners {
	&__content {
		padding: 45px 0;
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
		gap: 30px;
		background-color: #F5F1E9;
	}
	&__title {
		margin-bottom: 20px;
		max-width: 650px;
		font-size: 24px;
		line-height: 1;
		font-weight: 700;
		text-transform: uppercase;
		text-align: center;
	}
	&__list {
		display: flex;
		align-items: center;
		gap: 100px;
	}
	&__img {
		max-height: 29px;
	}
}
</style>
