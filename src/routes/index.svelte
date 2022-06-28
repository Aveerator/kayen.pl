<script>
	import Typewriter from 'svelte-typewriter'
</script>

<body>
	<div class="center">
		<Typewriter loop cursor={false} interval={200}>
			<p class="text-center">Kayen</p>
			<p class="text-center">Aviee</p>
			<p class="text-center">Adam </p>
		</Typewriter>
	</div>
	<div class="paragraph">
		<Typewriter>Programista, Full-Stack Web Developer, Grafik, Projektant Stron, Modder, Hacker.</Typewriter>
		<Typewriter delay={3000}>Nazywanie mnie którymkolwiek z tych tytułów byłoby overkillem :v</Typewriter>
	</div>
	<div class="footer">
		Made with svelte &lt;3 Adam\\Kayen//Aviee © 2022
	</div>
</body>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap');

	.footer {
		position: absolute;
		bottom: 0;
		width: 100%;
		text-align: center;
		font-size: 0.8rem;
		color: #000;
		background-color: #ffce8f;
		padding: 0.5rem;
	
		font-family: 'Lato', sans-serif;

	}
	.paragraph {
		font-family: 'Lato', sans-serif;
		font-size: 1.5rem;
		line-height: 2.5rem;
		text-align: center;
		margin-top: 2rem;
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
	}

	.text-center {
		font-size: 10em;
		font-weight: bold;
		color: #000;
		text-shadow: 0 0 20px #fff;
		font-family: 'Lato', sans-serif;
	}
	.center {
		position: absolute;
		top: 30%;
		left: 50%;
		transform: translate(-50%, -50%);
	}
	body {
		position: absolute;
		top: 0;
		bottom: 0;
		right: 0;
		left: 0;
		background-color: #ffddb1;
	}
</style>