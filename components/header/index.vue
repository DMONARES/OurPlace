<template>
	<div>
		<header class="header">
			<nav class="header__nav">
				<ul class="header__nav-list">
					<div class="header__nav-group">
						<li class="header__nav-item">
							<nuxt-link class="header__nav-link" to="/">
								Shop
							</nuxt-link>
						</li>
						<li class="header__nav-item">
							<nuxt-link class="header__nav-link" to="/">
								Always Pan
							</nuxt-link>
						</li>
					</div>
					<li class="header__nav-logo">
						<nuxt-link class="header__nav-link" to="/">
							<icons-logo />
						</nuxt-link>
					</li>
					<div class="header__nav-group">
						<li class="header__nav-item">
							<nuxt-link class="header__nav-link" to="/">
								Mission
							</nuxt-link>
						</li>
						<li class="header__nav-item">
							<nuxt-link class="header__nav-link" to="/">
								FAQs
							</nuxt-link>
						</li>
					</div>
				</ul>
			</nav>
			<div class="header__user">
				<icons-user />
			</div>
		</header>
	</div>
</template>

<style lang="scss">
.header {
	display: flex;
	align-items: center;
	justify-content: space-between;
	padding: 25px 48px;
	gap: 25px;

	&__nav {
		flex-grow: 1;

		&-list {
			display: flex;
			justify-content: space-between;
			align-items: center;
			width: 100%;
		}

		&-item { cursor: pointer; }

		&-link {
			color: $black;
			font-size: 13px;
			font-weight: 700;
			text-transform: uppercase;
			transition: color 0.3s;

			&:hover {
				color: $brown;
			}
		}

		&-group {
			display: flex;
			gap: 35px;
		}
	}
}
</style>
