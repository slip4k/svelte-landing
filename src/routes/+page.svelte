<script>
import { Button } from "$lib/components/ui/button";
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<div class="flex flex-col h-100dvh text-left m-auto">
		<h1 class="text-6xl font-bold max-w-[500px] ">This is your SaaS Landing Page</h1>
		<p class="mt-4 text-left">Get your application off the ground and running quickly</p>

		<div>
			<Button class="mt-8" variant="default">Contact Us</Button>
			<Button class="mt-8 ml-4" variant="outline">Pricing</Button>
		</div>

	</div>
</section>

