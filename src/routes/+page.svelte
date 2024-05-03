<script>
import { Button } from "$lib/components/ui/button";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="flex flex-col justify-center items-center h-100dvh">
		<h1>Hi!</h1>
		<Button class="mt-8" variant="default">This is a button</Button>
	</div>
</section>

