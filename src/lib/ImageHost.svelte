<div />

<style>
	div {
		position: absolute;
		top: 0;
		left: 0;
		background: url(/mobile/image-host.jpg) no-repeat center center fixed;
		background-size: cover;
		width: 100vw;
		height: 100vh;
		z-index: -1;
		opacity: 0.1;
	}

	@media screen and (min-width: 768px) {
		div {
			background: url(/tablet/image-host.jpg) no-repeat top right fixed;
			background-size: unset;
			opacity: 1;
		}
	}
</style>
