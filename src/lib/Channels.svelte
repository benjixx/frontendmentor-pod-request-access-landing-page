<div class="container">
	<img class="spotify" src="/desktop/spotify.svg" alt="Spotify" />
	<img class="apple-podcast" src="/desktop/apple-podcast.svg" alt="Apple Podcast" />
	<img class="google-podcasts" src="/desktop/google-podcasts.svg" alt="Google Podcasts" />
	<img class="pocket-casts" src="/desktop/pocket-casts.svg" alt="Pocket Casts" />
</div>

<style>
	.container {
		margin: 32px 0;

		display: flex;
		padding: 0 6px;
	}

	img {
		object-fit: contain;
		width: 100%;
		max-height: 100%;
		opacity: 0.6;
	}

	.container {
		height: 17px;
	}

	.apple-podcast,
	.google-podcasts {
		margin-left: 4px;
	}

	.pocket-casts {
		margin-left: 14px;
		margin-right: 6px;
	}

	@media screen and (min-width: 768px) {
		.container {
			height: 29px;
			max-width: 536px;
			padding: 0;
		}

		.spotify {
			margin-left: -12px;
		}

		.apple-podcast,
		.google-podcasts {
			margin-left: 8px;
		}

		.pocket-casts {
			margin-left: 24px;
			margin-right: 16px;
		}
	}
</style>
