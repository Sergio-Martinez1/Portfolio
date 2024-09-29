<script>
	import '../app.css';
</script>

<section class="w-full h-full flex flex-col">
	<header class="w-fit self-center h-14 flex items-center">
		<ul class="flex gap-x-10">
			<li class="hover:underline"><a href="/#">About me</a></li>
			<li class="hover:underline"><a href="/#">Projects</a></li>
			<li class="hover:underline"><a href="/#">Contact me</a></li>
		</ul>
	</header>
	<main>
		<slot />
	</main>
</section>
