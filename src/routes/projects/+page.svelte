<body class="flex h-full flex-col bg-zinc-50 dark:bg-black">
	<div class="fixed inset-0 flex justify-center sm:px-8">
		<div class="flex w-full max-w-7xl lg:px-8">
			<div class="w-full bg-white ring-1 ring-zinc-100 dark:bg-zinc-900 dark:ring-zinc-300/20" />
		</div>
	</div>
	<div class="relative">
		<header
			class="pointer-events-none relative z-50 flex flex-col"
			style="height:var(--header-height);margin-bottom:var(--header-mb)"
		>
			<div class="top-0 z-10 h-16 pt-6" style="position:var(--header-position)">
				<div
					class="sm:px-8 top-[var(--header-top,theme(spacing.6))] w-full"
					style="position:var(--header-inner-position)"
				>
					<div class="mx-auto max-w-7xl lg:px-8">
						<div class="relative px-4 sm:px-8 lg:px-12">
							<div class="mx-auto max-w-2xl lg:max-w-5xl">
								<div class="relative flex gap-4">
									<div class="flex flex-1">
										<div
											class="h-10 w-10 rounded-full bg-white/90 p-0.5 shadow-lg shadow-zinc-800/5 ring-1 ring-zinc-900/5 backdrop-blur dark:bg-zinc-800/90 dark:ring-white/10"
										>
											<a aria-label="Home" class="pointer-events-auto" href="/"
												><img
													alt=""
													width="512"
													height="512"
													decoding="async"
													data-nimg="1"
													class="rounded-full bg-zinc-100 object-cover dark:bg-zinc-800 h-9 w-9"
													sizes="2.25rem"
													src="images/grant.webp"
													style="color: transparent;"
												/></a
											>
										</div>
									</div>
									<div class="flex flex-1 justify-end md:justify-center">
										<div class="pointer-events-auto md:hidden" data-headlessui-state="" />
										<nav class="pointer-events-auto md:block">
											<ul
												class="flex rounded-full bg-white/90 px-3 text-sm font-medium text-zinc-800 shadow-lg shadow-zinc-800/5 ring-1 ring-zinc-900/5 backdrop-blur dark:bg-zinc-800/90 dark:text-zinc-200 dark:ring-white/10"
											>
												<li>
													<a
														class="relative block px-3 py-2 transition hover:text-red-400 dark:hover:text-red-400"
														href="/about">About</a
													>
												</li>
												<li>
													<a
														class="relative block px-3 py-2 transition text-red-400 dark:text-red-400"
														href="/projects"
														>Projects<span
															class="absolute inset-x-1 -bottom-px h-px bg-gradient-to-r from-red-500/0 via-red-500/40 to-red-500/0 dark:from-red-400/0 dark:via-red-400/40 dark:to-red-400/0"
														/></a
													>
												</li>
											</ul>
										</nav>
									</div>
									<div class="flex justify-end md:flex-1" />
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</header>
		<main>
			<div class="sm:px-8 mt-16 sm:mt-32">
				<div class="mx-auto max-w-7xl lg:px-8">
					<div class="relative px-4 sm:px-8 lg:px-12">
						<div class="mx-auto max-w-2xl lg:max-w-5xl">
							<header class="max-w-2xl">
								<h1
									class="text-4xl font-bold tracking-tight text-zinc-800 dark:text-zinc-100 sm:text-5xl"
								>
									Things I’ve made trying to put my dent in the universe.
								</h1>
								<p class="mt-6 text-base text-zinc-600 dark:text-zinc-400">
									I’ve worked on tons of little projects over the years but these are the ones that
									I’m most proud of. If you see something that piques your interest, check out the
									code and contribute if you have ideas for how it can be improved.
								</p>
							</header>
							<div class="mt-16 sm:mt-20">
								<ul class="grid md:grid-cols-2 gap-x-12 gap-y-16">
									<li class="group relative flex flex-col items-start">
										<div
											class="relative z-10 flex h-12 w-12 items-center justify-center rounded-full bg-white shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
										>
											<img
												alt=""
												loading="lazy"
												width="32"
												height="32"
												decoding="async"
												data-nimg="1"
												class="h-8 w-8 rounded-full"
												src="images/foodhaus.png"
												style="color: transparent;"
											/>
										</div>
										<h2 class="mt-6 text-base font-semibold text-zinc-800 dark:text-zinc-100">
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://foodhaus.vercel.app/"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">FoodHaus</span></a
											>
										</h2>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											Using The Meal DB, FoodHaus queries the API and returns a vast collection of
											recipes that can be sorted by country of origin or main ingredient. Built with
											React, NextJS, TailwindCSS, and hosted on Vercel, FoodHaus aims to be your one
											stop shop for seeking out new recipes to try.
										</p>
										<p
											class="relative z-10 mt-6 flex text-sm font-medium text-zinc-400 transition group-hover:text-red-400 dark:text-zinc-200"
										>
											<svg viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 flex-none"
												><path
													d="M15.712 11.823a.75.75 0 1 0 1.06 1.06l-1.06-1.06Zm-4.95 1.768a.75.75 0 0 0 1.06-1.06l-1.06 1.06Zm-2.475-1.414a.75.75 0 1 0-1.06-1.06l1.06 1.06Zm4.95-1.768a.75.75 0 1 0-1.06 1.06l1.06-1.06Zm3.359.53-.884.884 1.06 1.06.885-.883-1.061-1.06Zm-4.95-2.12 1.414-1.415L12 6.344l-1.415 1.413 1.061 1.061Zm0 3.535a2.5 2.5 0 0 1 0-3.536l-1.06-1.06a4 4 0 0 0 0 5.656l1.06-1.06Zm4.95-4.95a2.5 2.5 0 0 1 0 3.535L17.656 12a4 4 0 0 0 0-5.657l-1.06 1.06Zm1.06-1.06a4 4 0 0 0-5.656 0l1.06 1.06a2.5 2.5 0 0 1 3.536 0l1.06-1.06Zm-7.07 7.07.176.177 1.06-1.06-.176-.177-1.06 1.06Zm-3.183-.353.884-.884-1.06-1.06-.884.883 1.06 1.06Zm4.95 2.121-1.414 1.414 1.06 1.06 1.415-1.413-1.06-1.061Zm0-3.536a2.5 2.5 0 0 1 0 3.536l1.06 1.06a4 4 0 0 0 0-5.656l-1.06 1.06Zm-4.95 4.95a2.5 2.5 0 0 1 0-3.535L6.344 12a4 4 0 0 0 0 5.656l1.06-1.06Zm-1.06 1.06a4 4 0 0 0 5.657 0l-1.061-1.06a2.5 2.5 0 0 1-3.535 0l-1.061 1.06Zm7.07-7.07-.176-.177-1.06 1.06.176.178 1.06-1.061Z"
													fill="currentColor"
												/></svg
											><span class="ml-2">foodhaus.vercel.app</span>
										</p>
									</li>
									<li class="group relative flex flex-col items-start">
										<div
											class="relative z-10 flex h-12 w-12 items-center justify-center rounded-full bg-white shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
										>
											<img
												alt=""
												loading="lazy"
												width="32"
												height="32"
												decoding="async"
												data-nimg="1"
												class="h-8 w-8 rounded-full"
												src="images/crypto.png"
											/>
										</div>
										<h2 class="mt-6 text-base font-semibold text-zinc-800 dark:text-zinc-100">
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://crypto-prices-gg.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">Cryptocurrency Prices</span></a
											>
										</h2>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											Built with React, NextJS, TainwindCSS, and hosted on Vercel, this site pulls
											from the CoinGecko API and provides chart data on the top 100 Cryptocurrencies
											visualied with ChartJS.
										</p>
										<p
											class="relative z-10 mt-6 flex text-sm font-medium text-zinc-400 transition group-hover:text-red-400 dark:text-zinc-200"
										>
											<svg viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 flex-none"
												><path
													d="M15.712 11.823a.75.75 0 1 0 1.06 1.06l-1.06-1.06Zm-4.95 1.768a.75.75 0 0 0 1.06-1.06l-1.06 1.06Zm-2.475-1.414a.75.75 0 1 0-1.06-1.06l1.06 1.06Zm4.95-1.768a.75.75 0 1 0-1.06 1.06l1.06-1.06Zm3.359.53-.884.884 1.06 1.06.885-.883-1.061-1.06Zm-4.95-2.12 1.414-1.415L12 6.344l-1.415 1.413 1.061 1.061Zm0 3.535a2.5 2.5 0 0 1 0-3.536l-1.06-1.06a4 4 0 0 0 0 5.656l1.06-1.06Zm4.95-4.95a2.5 2.5 0 0 1 0 3.535L17.656 12a4 4 0 0 0 0-5.657l-1.06 1.06Zm1.06-1.06a4 4 0 0 0-5.656 0l1.06 1.06a2.5 2.5 0 0 1 3.536 0l1.06-1.06Zm-7.07 7.07.176.177 1.06-1.06-.176-.177-1.06 1.06Zm-3.183-.353.884-.884-1.06-1.06-.884.883 1.06 1.06Zm4.95 2.121-1.414 1.414 1.06 1.06 1.415-1.413-1.06-1.061Zm0-3.536a2.5 2.5 0 0 1 0 3.536l1.06 1.06a4 4 0 0 0 0-5.656l-1.06 1.06Zm-4.95 4.95a2.5 2.5 0 0 1 0-3.535L6.344 12a4 4 0 0 0 0 5.656l1.06-1.06Zm-1.06 1.06a4 4 0 0 0 5.657 0l-1.061-1.06a2.5 2.5 0 0 1-3.535 0l-1.061 1.06Zm7.07-7.07-.176-.177-1.06 1.06.176.178 1.06-1.061Z"
													fill="currentColor"
												/></svg
											><span class="ml-2">crypto-prices-gg.vercel.app</span>
										</p>
									</li>
									<li class="group relative flex flex-col items-start">
										<div
											class="relative z-10 flex h-12 w-12 items-center justify-center rounded-full bg-white shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
										>
											<img
												alt=""
												loading="lazy"
												width="32"
												height="32"
												decoding="async"
												data-nimg="1"
												class="h-8 w-8 rounded-full"
												src="images/halcyon.png"
												style="color: transparent;"
											/>
										</div>
										<h2 class="mt-6 text-base font-semibold text-zinc-800 dark:text-zinc-100">
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://halcyon-cloth.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">Halcyon Cloth</span></a
											>
										</h2>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											Halcyon Cloth, a work in progress, is a full stack e-commerce website. Built
											with SvelteKit, designed with TailwindCSS, and hosted on Vercel. Halcyon Cloth
											offers unique designs for a new generation.
										</p>
										<p
											class="relative z-10 mt-6 flex text-sm font-medium text-zinc-400 transition group-hover:text-red-400 dark:text-zinc-200"
										>
											<svg viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 flex-none"
												><path
													d="M15.712 11.823a.75.75 0 1 0 1.06 1.06l-1.06-1.06Zm-4.95 1.768a.75.75 0 0 0 1.06-1.06l-1.06 1.06Zm-2.475-1.414a.75.75 0 1 0-1.06-1.06l1.06 1.06Zm4.95-1.768a.75.75 0 1 0-1.06 1.06l1.06-1.06Zm3.359.53-.884.884 1.06 1.06.885-.883-1.061-1.06Zm-4.95-2.12 1.414-1.415L12 6.344l-1.415 1.413 1.061 1.061Zm0 3.535a2.5 2.5 0 0 1 0-3.536l-1.06-1.06a4 4 0 0 0 0 5.656l1.06-1.06Zm4.95-4.95a2.5 2.5 0 0 1 0 3.535L17.656 12a4 4 0 0 0 0-5.657l-1.06 1.06Zm1.06-1.06a4 4 0 0 0-5.656 0l1.06 1.06a2.5 2.5 0 0 1 3.536 0l1.06-1.06Zm-7.07 7.07.176.177 1.06-1.06-.176-.177-1.06 1.06Zm-3.183-.353.884-.884-1.06-1.06-.884.883 1.06 1.06Zm4.95 2.121-1.414 1.414 1.06 1.06 1.415-1.413-1.06-1.061Zm0-3.536a2.5 2.5 0 0 1 0 3.536l1.06 1.06a4 4 0 0 0 0-5.656l-1.06 1.06Zm-4.95 4.95a2.5 2.5 0 0 1 0-3.535L6.344 12a4 4 0 0 0 0 5.656l1.06-1.06Zm-1.06 1.06a4 4 0 0 0 5.657 0l-1.061-1.06a2.5 2.5 0 0 1-3.535 0l-1.061 1.06Zm7.07-7.07-.176-.177-1.06 1.06.176.178 1.06-1.061Z"
													fill="currentColor"
												/></svg
											><span class="ml-2">halcyon-cloth.vercel.app</span>
										</p>
									</li>
									<li class="group relative flex flex-col items-start">
										<div
											class="relative z-10 flex h-12 w-12 items-center justify-center rounded-full bg-white shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
										>
											<img
												alt=""
												loading="lazy"
												width="32"
												height="32"
												decoding="async"
												data-nimg="1"
												class="h-8 w-8 rounded-full"
												src="images/granthaus.png"
											/>
										</div>
										<h2 class="mt-6 text-base font-semibold text-zinc-800 dark:text-zinc-100">
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://homescope.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">HomeScope</span></a
											>
										</h2>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											HomeScope is a Realty website built with React, NextJS, ChakraUI, and hosted
											on Vercel. Search and filter to your hearts desire to find your next dream
											home.
										</p>
										<p
											class="relative z-10 mt-6 flex text-sm font-medium text-zinc-400 transition group-hover:text-red-400 dark:text-zinc-200"
										>
											<svg viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 flex-none"
												><path
													d="M15.712 11.823a.75.75 0 1 0 1.06 1.06l-1.06-1.06Zm-4.95 1.768a.75.75 0 0 0 1.06-1.06l-1.06 1.06Zm-2.475-1.414a.75.75 0 1 0-1.06-1.06l1.06 1.06Zm4.95-1.768a.75.75 0 1 0-1.06 1.06l1.06-1.06Zm3.359.53-.884.884 1.06 1.06.885-.883-1.061-1.06Zm-4.95-2.12 1.414-1.415L12 6.344l-1.415 1.413 1.061 1.061Zm0 3.535a2.5 2.5 0 0 1 0-3.536l-1.06-1.06a4 4 0 0 0 0 5.656l1.06-1.06Zm4.95-4.95a2.5 2.5 0 0 1 0 3.535L17.656 12a4 4 0 0 0 0-5.657l-1.06 1.06Zm1.06-1.06a4 4 0 0 0-5.656 0l1.06 1.06a2.5 2.5 0 0 1 3.536 0l1.06-1.06Zm-7.07 7.07.176.177 1.06-1.06-.176-.177-1.06 1.06Zm-3.183-.353.884-.884-1.06-1.06-.884.883 1.06 1.06Zm4.95 2.121-1.414 1.414 1.06 1.06 1.415-1.413-1.06-1.061Zm0-3.536a2.5 2.5 0 0 1 0 3.536l1.06 1.06a4 4 0 0 0 0-5.656l-1.06 1.06Zm-4.95 4.95a2.5 2.5 0 0 1 0-3.535L6.344 12a4 4 0 0 0 0 5.656l1.06-1.06Zm-1.06 1.06a4 4 0 0 0 5.657 0l-1.061-1.06a2.5 2.5 0 0 1-3.535 0l-1.061 1.06Zm7.07-7.07-.176-.177-1.06 1.06.176.178 1.06-1.061Z"
													fill="currentColor"
												/></svg
											><span class="ml-2">homescope.vercel.app</span>
										</p>
									</li>
									<li class="group relative flex flex-col items-start">
										<div
											class="relative z-10 flex h-12 w-12 items-center justify-center rounded-full bg-white shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
										>
											<img
												alt=""
												loading="lazy"
												width="32"
												height="32"
												decoding="async"
												data-nimg="1"
												class="h-8 w-8 rounded-full"
												src="images/drinkhaus.png"
												style="color: transparent;"
											/>
										</div>
										<h2 class="mt-6 text-base font-semibold text-zinc-800 dark:text-zinc-100">
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://drinkhaus.vercel.app/"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">DrinkHaus</span></a
											>
										</h2>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											The sister site to FoodHaus, DrinkHaus offers a vast selection of Alcoholic
											and Non-Alcoholic cocktails to excite your next party.
										</p>
										<p
											class="relative z-10 mt-6 flex text-sm font-medium text-zinc-400 transition group-hover:text-red-400 dark:text-zinc-200"
										>
											<svg viewBox="0 0 24 24" aria-hidden="true" class="h-6 w-6 flex-none"
												><path
													d="M15.712 11.823a.75.75 0 1 0 1.06 1.06l-1.06-1.06Zm-4.95 1.768a.75.75 0 0 0 1.06-1.06l-1.06 1.06Zm-2.475-1.414a.75.75 0 1 0-1.06-1.06l1.06 1.06Zm4.95-1.768a.75.75 0 1 0-1.06 1.06l1.06-1.06Zm3.359.53-.884.884 1.06 1.06.885-.883-1.061-1.06Zm-4.95-2.12 1.414-1.415L12 6.344l-1.415 1.413 1.061 1.061Zm0 3.535a2.5 2.5 0 0 1 0-3.536l-1.06-1.06a4 4 0 0 0 0 5.656l1.06-1.06Zm4.95-4.95a2.5 2.5 0 0 1 0 3.535L17.656 12a4 4 0 0 0 0-5.657l-1.06 1.06Zm1.06-1.06a4 4 0 0 0-5.656 0l1.06 1.06a2.5 2.5 0 0 1 3.536 0l1.06-1.06Zm-7.07 7.07.176.177 1.06-1.06-.176-.177-1.06 1.06Zm-3.183-.353.884-.884-1.06-1.06-.884.883 1.06 1.06Zm4.95 2.121-1.414 1.414 1.06 1.06 1.415-1.413-1.06-1.061Zm0-3.536a2.5 2.5 0 0 1 0 3.536l1.06 1.06a4 4 0 0 0 0-5.656l-1.06 1.06Zm-4.95 4.95a2.5 2.5 0 0 1 0-3.535L6.344 12a4 4 0 0 0 0 5.656l1.06-1.06Zm-1.06 1.06a4 4 0 0 0 5.657 0l-1.061-1.06a2.5 2.5 0 0 1-3.535 0l-1.061 1.06Zm7.07-7.07-.176-.177-1.06 1.06.176.178 1.06-1.061Z"
													fill="currentColor"
												/></svg
											><span class="ml-2">drinkhaus.vercel.app/</span>
										</p>
									</li>
								</ul>
							</div>
						</div>
					</div>
				</div>
			</div>
		</main>
		<footer class="mt-32">
			<div class="sm:px-8">
				<div class="mx-auto max-w-7xl lg:px-8">
					<div class="border-t border-zinc-100 pb-16 pt-10 dark:border-zinc-700/40">
						<div class="relative px-4 sm:px-8 lg:px-12">
							<div class="mx-auto max-w-2xl lg:max-w-5xl">
								<div class="flex flex-col items-center justify-between gap-6 sm:flex-row">
									<div class="flex gap-6 text-sm font-medium text-zinc-800 dark:text-zinc-200">
										<a class="transition hover:text-red-400 dark:hover:text-red-400" href="/about"
											>About</a
										><a
											class="transition hover:text-red-400 dark:hover:text-red-400"
											href="/projects">Projects</a
										>
									</div>
									<p class="text-sm text-zinc-400 dark:text-zinc-500">
										© 2023 Grant Gariepy. All rights reserved.
									</p>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</footer>
	</div>
</body>
