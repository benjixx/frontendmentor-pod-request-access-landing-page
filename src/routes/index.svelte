<script>
	import Channels from '$lib/Channels.svelte';
	import Headline from '$lib/Headline.svelte';
	import ImageHost from '$lib/ImageHost.svelte';
	import Intro from '$lib/Intro.svelte';
	import Logo from '$lib/Logo.svelte';
	import PatternDots from '$lib/PatternDots.svelte';
	import RequestAccessForm from '$lib/RequestAccessForm.svelte';
</script>

<main>
	<Logo />
	<div class="content">
		<div class="wrapper-headline">
			<Headline />
		</div>
		<div class="wrapper-intro">
			<Intro />
		</div>
		<div class="wrapper-channels">
			<Channels />
		</div>
		<div class="wrapper-request-access-form">
			<RequestAccessForm />
		</div>
	</div>
	<PatternDots />
	<ImageHost />
</main>

<style>
	main {
		margin: 24px;
	}

	@media screen and (min-width: 768px) {
		main {
			margin: 39px;
		}
	}

	@media screen and (min-width: 1440px) {
		main {
			margin: 130px 0 130px 165px;
		}
	}

	.content {
		display: flex;
		/* ATTENTION: using flex here automatically gets rid of collapsing margins */
		flex-direction: column;
	}

	@media screen and (min-width: 768px) {
		.content {
			margin: 152px 0 0 0;
			max-width: 635px;
			padding-top: 92px;
			padding-right: 32px;

			background: #121725;
		}

		.wrapper-headline {
			order: 1;
		}
		.wrapper-intro {
			order: 2;
		}
		.wrapper-request-access-form {
			order: 3;
		}
		.wrapper-channels {
			order: 4;
		}
	}

	@media screen and (min-width: 1440px) {
		.content {
			margin: 76px 0 0 0;
		}
	}
</style>
