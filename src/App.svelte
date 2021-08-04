<script>
import AboutMe from "./AboutMe.svelte";
import HowItStarted from "./HowItStarted.svelte";


</script>

<main>
	<h1>Welcome to My Space!</h1>
	<AboutMe />
  <HowItStarted />
</main>

<style>
  main {
        background-image: url("https://media.giphy.com/media/BHNfhgU63qrks/source.gif");
        background-size:cover;
        background-repeat: no-repeat;
        background-attachment: fixed;
    }


	main {
		text-align: left;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #E7FFAA;
		text-transform: uppercase;
		font-size: 3em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>