<script>
  const extensionsList = [
    {
      title: '',
      id: '',
      img: '',
      description: '',
      price: ''
    }
  ]
</script>

<!-- product-grid - start -->
<div class="bg-white py-6 sm:py-8 lg:py-12">
	<div class="mx-auto max-w-screen-2xl px-4 md:px-8">
		<!-- text - start -->
		<div class="mb-10 md:mb-16">
			<h2 class="mb-4 text-center text-2xl font-bold text-gray-800 md:mb-6 lg:text-3xl">
				Rozszerzenia gry
			</h2>

			<p class="mx-auto max-w-screen-md text-center text-gray-500 md:text-lg">
				This is a section of some simple filler text, also known as placeholder text. It shares some
				characteristics of a real written text but is random or otherwise generated.
			</p>
		</div>
		<!-- text - end -->

		<div class="grid gap-x-4 gap-y-8 sm:grid-cols-2 md:gap-x-6 lg:grid-cols-3 xl:grid-cols-4">
			<!-- product - start -->
      {#each extensionsList as extension}
			<div>
				<a
					href="#"
					class="group relative mb-2 block h-96 overflow-hidden rounded-lg bg-gray-100 shadow-lg lg:mb-3"
				>
					<img
						src="https://images.unsplash.com/photo-1552374196-1ab2a1c593e8?auto=format&q=75&fit=crop&crop=top&w=600&h=700"
						loading="lazy"
						alt="Photo by Austin Wade"
						class="h-full w-full object-cover object-center transition duration-200 group-hover:scale-110"
					/>

					<div class="absolute left-0 bottom-2 flex gap-2">
						<span
							class="rounded-r-lg bg-red-500 px-3 py-1.5 text-sm font-semibold uppercase tracking-wider text-white"
							>-50%</span
						>
						<span
							class="rounded-lg bg-white px-3 py-1.5 text-sm font-bold uppercase tracking-wider text-gray-800"
							>New</span
						>
					</div>
				</a>

				<div class="flex items-start justify-between gap-2 px-2">
					<div class="flex flex-col">
						<a
							href="#"
							class="text-lg font-bold text-gray-800 transition duration-100 hover:text-gray-500 lg:text-xl"
							>Fancy Outfit</a
						>
						<span class="text-gray-500">by Fancy Brand</span>
					</div>

					<div class="flex flex-col items-end">
						<span class="font-bold text-gray-600 lg:text-lg">$19.99</span>
						<span class="text-sm text-red-500 line-through">$39.99</span>
					</div>
				</div>
			</div>
      {/each}
			<!-- product - end -->
		</div>
	</div>
</div>
<!-- product-grid - end -->
