<script>
import { Button } from "$lib/components/ui/button";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="flex flex-col justify-center items-center h-100dvh">
		<h1 class="text-6xl font-bold max-w-[500px] text-center">This is your SaaS Landing Page</h1>
		<p class="mt-4">Get your application off the ground and running quickly</p>

		<Button class="mt-8" variant="default">This is a button</Button>
	</div>
</section>

