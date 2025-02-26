
<script>
	import { page } from '$app/stores';
</script>

<main>
<div class="flex justify-center mx-auto p-4">

<div class="grid">

{#if $page.error}
<h1 class="text-4xl font-bold text-danger-800 text-center">{$page.error.message}</h1>
{/if}

<h1 class="pt-4 text-3xl font-bold text-danger-800 text-center">Código de Error: {$page.status}</h1>

	
</div>
</div>

</main>
