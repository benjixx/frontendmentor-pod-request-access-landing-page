<div class="container">
	<div class="pattern-dots" />
</div>

<style>
	.container {
		display: none;
	}

	@media screen and (min-width: 768px) {
		.container {
			display: block;
		}

		.pattern-dots {
			width: 232px;
			height: 104px;
			background: url(/desktop/bg-pattern-dots.svg) no-repeat;
			transform: translate(-9px, 120px);
		}
	}

	@media screen and (min-width: 1440px) {
		.pattern-dots {
			float: right;
			transform: translateY(calc(-50% - 32px));
		}
	}
</style>
