<script>
  import Button from "./ui/button/button.svelte";
</script>

<nav class="flex items-center justify-between w-full my-4 m-auto px-12">
  <h1 class="font-bold text-6xl">js.</h1>
  <ul class="flex items-center gap-x-4">
    <li>
      <a class="hover:underline" href="/">About</a>
    </li>
    <li>
      <a class="hover:underline" href="/">Blog</a>
    </li>
    <li>
      <Button variant="default">Contact Us</Button>
    </li>
  </ul>
</nav>