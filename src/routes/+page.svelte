<script>
	let count = 0;

	import {
		Button,
	} from 'svelte-ux';

	
	function handleClick() {
		count += 1;
	}
	
</script>

<main class="p-4 grid place-items-center content-center">
	<h1 class="text-2xl font-semibold m-4 text-secondary">
		Hello World, Svelte-ux!
	</h1>

    <Button variant="fill" color="primary" on:click={handleClick}> Click me!</Button>

	<div class="p-3">
	Clicks= {count}
	</div>

</main>
