<form action="">
	<input type="text" placeholder="Email address" />
	<button>Request Access</button>
</form>

<style>
	form {
		margin-top: 16px;
	}

	input,
	button {
		box-sizing: border-box;

		display: block;
		width: 100%;

		border: 0;

		font-weight: 700;
		font-size: 14px;
		line-height: 28px;

		border-radius: 23px;
		height: 46px;
	}

	input {
		background: #2c344b;
		padding-left: 32px;
		color: #fff;
	}

	button {
		margin-top: 16px;
		background: #54e6af;
	}

	button:hover {
		background: #b3ffe2;
	}

	@media screen and (min-width: 768px) {
		form {
			margin-top: 0;
			margin-bottom: 32px;
			display: inline-block;
			background: #2c344b;
			border: 5px solid #2c344b;
			border-radius: 28px;
			max-width: 428px;
		}

		input,
		button {
			display: inline-block;
			width: unset;
			margin: 0;
		}

		input {
			width: 240px;
		}

		button {
			padding: 8px 24px;
		}
	}
</style>
