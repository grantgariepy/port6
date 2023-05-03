<body class="flex h-full flex-col bg-zinc-50 dark:bg-black">
	<div class="fixed inset-0 flex justify-center sm:px-8">
		<div class="flex w-full max-w-7xl lg:px-8">
			<div class="w-full bg-white ring-1 ring-zinc-100 dark:bg-zinc-900 dark:ring-zinc-300/20" />
		</div>
	</div>
	<div class="relative">
		<header class="pointer-events-none relative z-50 flex flex-col">
			<div class="order-last mt-[calc(theme(spacing.16)-theme(spacing.3))]" />
			<div class="sm:px-8 top-0 order-last -mb-3 pt-3">
				<div class="mx-auto max-w-7xl lg:px-8">
					<div class="relative px-4 sm:px-8 lg:px-12">
						<div class="mx-auto max-w-2xl lg:max-w-5xl">
							<div class=" w-full">
								<div class="relative">
									<div
										class="absolute left-0 top-3 origin-left transition-opacity h-10 w-10 rounded-full p-0.5 shadow-lg"
									/>
									<a
										aria-label="Home"
										class="block h-16 w-16 origin-left pointer-events-auto"
										href="/"
										><img
											alt=""
											width="512"
											height="512"
											decoding="async"
											class="rounded-full object-cover h-16 w-16"
											sizes="4rem"
											src="images/grant.webp"
										/></a
									>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="top-0 z-10 h-16 pt-6" style="position:var(--header-position)">
				<div
					class="sm:px-8 top-[var(--header-top,theme(spacing.6))] w-full"
					style="position:var(--header-inner-position)"
				>
					<div class="mx-auto max-w-7xl lg:px-8">
						<div class="relative px-4 sm:px-8 lg:px-12">
							<div class="mx-auto max-w-2xl lg:max-w-5xl">
								<div class="relative flex gap-4">
									<div class="flex flex-1" />
									<div class="flex flex-1 justify-end md:justify-center">
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
														class="relative block px-3 py-2 transition hover:text-red-400 dark:hover:text-red-400"
														href="/projects">Projects</a
													>
												</li>
											</ul>
										</nav>
									</div>
									<div class="flex justify-end md:flex-1">
										<div class="pointer-events-auto" />
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</header>
		<div style="height:var(--content-offset)" />
		<main>
			<div class="sm:px-8 mt-9">
				<div class="mx-auto max-w-7xl lg:px-8">
					<div class="relative px-4 sm:px-8 lg:px-12">
						<div class="mx-auto max-w-2xl lg:max-w-5xl">
							<div class="max-w-2xl">
								<h1
									class="text-4xl font-bold tracking-tight text-zinc-800 dark:text-zinc-100 sm:text-5xl"
								>
									Grant Gariepy
								</h1>
								<p class="mt-6 text-base text-zinc-600 dark:text-zinc-400">
									I'm Grant, a software developer based in Utah. I strive to bring both technical
									expertise and artistic finesse to my work, creating solutions that not only
									function flawlessly but also delight and inspire those who use them.
								</p>
								<div class="mt-6 flex gap-6">
									<a
										class="group -m-1 p-1"
										aria-label="Follow on GitHub"
										href="https://github.com/grantgariepy"
										><svg
											viewBox="0 0 24 24"
											aria-hidden="true"
											class="h-6 w-6 fill-zinc-500 transition group-hover:fill-zinc-600 dark:fill-zinc-400 dark:group-hover:fill-zinc-300"
											><path
												fill-rule="evenodd"
												clip-rule="evenodd"
												d="M12 2C6.475 2 2 6.588 2 12.253c0 4.537 2.862 8.369 6.838 9.727.5.09.687-.218.687-.487 0-.243-.013-1.05-.013-1.91C7 20.059 6.35 18.957 6.15 18.38c-.113-.295-.6-1.205-1.025-1.448-.35-.192-.85-.667-.013-.68.788-.012 1.35.744 1.538 1.051.9 1.551 2.338 1.116 2.912.846.088-.666.35-1.115.638-1.371-2.225-.256-4.55-1.14-4.55-5.062 0-1.115.387-2.038 1.025-2.756-.1-.256-.45-1.307.1-2.717 0 0 .837-.269 2.75 1.051.8-.23 1.65-.346 2.5-.346.85 0 1.7.115 2.5.346 1.912-1.333 2.75-1.05 2.75-1.05.55 1.409.2 2.46.1 2.716.637.718 1.025 1.628 1.025 2.756 0 3.934-2.337 4.806-4.562 5.062.362.32.675.936.675 1.897 0 1.371-.013 2.473-.013 2.82 0 .268.188.589.688.486a10.039 10.039 0 0 0 4.932-3.74A10.447 10.447 0 0 0 22 12.253C22 6.588 17.525 2 12 2Z"
											/></svg
										></a
									><a
										class="group -m-1 p-1"
										aria-label="Follow on LinkedIn"
										href="https://www.linkedin.com/in/grantgariepy/"
										><svg
											viewBox="0 0 24 24"
											aria-hidden="true"
											class="h-6 w-6 fill-zinc-500 transition group-hover:fill-zinc-600 dark:fill-zinc-400 dark:group-hover:fill-zinc-300"
											><path
												d="M18.335 18.339H15.67v-4.177c0-.996-.02-2.278-1.39-2.278-1.389 0-1.601 1.084-1.601 2.205v4.25h-2.666V9.75h2.56v1.17h.035c.358-.674 1.228-1.387 2.528-1.387 2.7 0 3.2 1.778 3.2 4.091v4.715zM7.003 8.575a1.546 1.546 0 01-1.548-1.549 1.548 1.548 0 111.547 1.549zm1.336 9.764H5.666V9.75H8.34v8.589zM19.67 3H4.329C3.593 3 3 3.58 3 4.297v15.406C3 20.42 3.594 21 4.328 21h15.338C20.4 21 21 20.42 21 19.703V4.297C21 3.58 20.4 3 19.666 3h.003z"
											/></svg
										></a
									>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="mt-16 sm:mt-20">
				<div class="-my-4 flex justify-center gap-5 overflow-hidden py-4 sm:gap-8">
					<div
						class="relative aspect-[9/10] w-44 flex-none overflow-hidden rounded-xl bg-zinc-100 dark:bg-zinc-800 sm:w-72 sm:rounded-2xl rotate-2"
					>
						<img
							alt=""
							loading="lazy"
							width="3744"
							height="5616"
							decoding="async"
							data-nimg="1"
							class="absolute inset-0 h-full w-full object-cover"
							style="color:transparent"
							sizes="(min-width: 640px) 18rem, 11rem"
							src="images/grant2.jpg"
						/>
					</div>
					<div
						class="relative aspect-[9/10] w-44 flex-none overflow-hidden rounded-xl bg-zinc-100 dark:bg-zinc-800 sm:w-72 sm:rounded-2xl -rotate-2"
					>
						<img
							alt=""
							loading="lazy"
							width="3936"
							height="2624"
							decoding="async"
							data-nimg="1"
							class="absolute inset-0 h-full w-full object-cover"
							style="color:transparent"
							sizes="(min-width: 640px) 18rem, 11rem"
							src="images/grant3.jpg"
						/>
					</div>
					<div
						class="relative aspect-[9/10] w-44 flex-none overflow-hidden rounded-xl bg-zinc-100 dark:bg-zinc-800 sm:w-72 sm:rounded-2xl -rotate-2"
					>
						<img
							alt=""
							loading="lazy"
							width="4240"
							height="2384"
							decoding="async"
							data-nimg="1"
							class="absolute inset-0 h-full w-full object-cover"
							style="color:transparent"
							sizes="(min-width: 640px) 18rem, 11rem"
							src="images/grant5.JPG"
						/>
					</div>
					<div
						class="relative aspect-[9/10] w-44 flex-none overflow-hidden rounded-xl bg-zinc-100 dark:bg-zinc-800 sm:w-72 sm:rounded-2xl rotate-2"
					>
						<img
							alt=""
							loading="lazy"
							width="5760"
							height="3840"
							decoding="async"
							data-nimg="1"
							class="absolute inset-0 h-full w-full object-cover"
							style="color:transparent"
							sizes="(min-width: 640px) 18rem, 11rem"
							src="images/grant4.jpg"
						/>
					</div>
					<div
						class="relative aspect-[9/10] w-44 flex-none overflow-hidden rounded-xl bg-zinc-100 dark:bg-zinc-800 sm:w-72 sm:rounded-2xl rotate-2"
					>
						<img
							alt=""
							loading="lazy"
							width="2400"
							height="3000"
							decoding="async"
							data-nimg="1"
							class="absolute inset-0 h-full w-full object-cover"
							style="color:transparent"
							sizes="(min-width: 640px) 18rem, 11rem"
							src="images/grant6.jpeg"
						/>
					</div>
				</div>
			</div>
			<div class="sm:px-8 mt-24 md:mt-28">
				<div class="mx-auto max-w-7xl lg:px-8">
					<div class="relative px-4 sm:px-8 lg:px-12">
						<div class="mx-auto max-w-2xl lg:max-w-5xl">
							<div class="mx-auto grid max-w-xl grid-cols-1 gap-y-20 lg:max-w-none lg:grid-cols-2">
								<div class="flex flex-col gap-16">
									<article class="group relative flex flex-col items-start">
										<h2
											class="text-base font-semibold tracking-tight text-zinc-800 dark:text-zinc-100"
										>
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://halcyon-cloth.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10"
													>Introducing Halcyon: Clothing for a new generation</span
												></a
											>
										</h2>
										<time
											class="relative z-10 order-first mb-3 flex items-center text-sm text-zinc-400 dark:text-zinc-500 pl-3.5"
											datetime="2022-09-02"
											><span class="absolute inset-y-0 left-0 flex items-center" aria-hidden="true"
												><span class="h-4 w-0.5 rounded-full bg-zinc-200 dark:bg-zinc-500" /></span
											>April 3, 2023</time
										>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											Halcyon is a daring and visionary clothing brand that fearlessly pushes the
											boundaries of fashion, creating cutting-edge designs that challenge
											conventional norms and inspire a new generation of trendsetters. With its bold
											use of colors, textures, and fabrics, Halcyon is carving a unique and
											unmistakable path in the world of fashion.
										</p>
										<div
											aria-hidden="true"
											class="relative z-10 mt-4 flex items-center text-sm font-medium text-red-400"
										>
											Visit Site<svg
												viewBox="0 0 16 16"
												fill="none"
												aria-hidden="true"
												class="ml-1 h-4 w-4 stroke-current"
												><path
													d="M6.75 5.75 9.25 8l-2.5 2.25"
													stroke-width="1.5"
													stroke-linecap="round"
													stroke-linejoin="round"
												/></svg
											>
										</div>
									</article>
									<article class="group relative flex flex-col items-start">
										<h2
											class="text-base font-semibold tracking-tight text-zinc-800 dark:text-zinc-100"
										>
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://foodhaus.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">FoodHaus, our one stop shop for recipes</span
												></a
											>
										</h2>
										<time
											class="relative z-10 order-first mb-3 flex items-center text-sm text-zinc-400 dark:text-zinc-500 pl-3.5"
											datetime="2022-09-05"
											><span class="absolute inset-y-0 left-0 flex items-center" aria-hidden="true"
												><span class="h-4 w-0.5 rounded-full bg-zinc-200 dark:bg-zinc-500" /></span
											>December 2, 2022</time
										>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											Foodhaus is a culinary haven, offering a plethora of mouth-watering recipes to
											satisfy every taste bud and culinary inclination. With its easy-to-navigate
											interface and user-friendly features, Foodhaus is the go-to destination for
											foodies and home chefs alike in search of delicious and inspiring meal ideas.
										</p>
										<div
											aria-hidden="true"
											class="relative z-10 mt-4 flex items-center text-sm font-medium text-red-400"
										>
											Visit Site<svg
												viewBox="0 0 16 16"
												fill="none"
												aria-hidden="true"
												class="ml-1 h-4 w-4 stroke-current"
												><path
													d="M6.75 5.75 9.25 8l-2.5 2.25"
													stroke-width="1.5"
													stroke-linecap="round"
													stroke-linejoin="round"
												/></svg
											>
										</div>
									</article>

									<article class="group relative flex flex-col items-start">
										<h2
											class="text-base font-semibold tracking-tight text-zinc-800 dark:text-zinc-100"
										>
											<div
												class="absolute -inset-x-4 -inset-y-6 z-0 scale-95 bg-zinc-50 opacity-0 transition group-hover:scale-100 group-hover:opacity-100 dark:bg-zinc-800/50 sm:-inset-x-6 sm:rounded-2xl"
											/>
											<a href="https://drinkhaus.vercel.app"
												><span
													class="absolute -inset-x-4 -inset-y-6 z-20 sm:-inset-x-6 sm:rounded-2xl"
												/><span class="relative z-10">DrinkHaus, this sister site of FoodHaus</span
												></a
											>
										</h2>
										<time
											class="relative z-10 order-first mb-3 flex items-center text-sm text-zinc-400 dark:text-zinc-500 pl-3.5"
											datetime="2022-07-14"
											><span class="absolute inset-y-0 left-0 flex items-center" aria-hidden="true"
												><span class="h-4 w-0.5 rounded-full bg-zinc-200 dark:bg-zinc-500" /></span
											>January 25, 2023</time
										>
										<p class="relative z-10 mt-2 text-sm text-zinc-600 dark:text-zinc-400">
											DrinkHaus, the sister site to Foodhaus, is a cocktail lover's paradise,
											boasting an extensive collection of tantalizing drink recipes that are sure to
											impress even the most discerning mixologists. From classic cocktails to
											innovative concoctions, DrinkHaus offers a refreshing and exciting approach to
											the art of mixology.
										</p>
										<div
											aria-hidden="true"
											class="relative z-10 mt-4 flex items-center text-sm font-medium text-red-400"
										>
											Visit Site<svg
												viewBox="0 0 16 16"
												fill="none"
												aria-hidden="true"
												class="ml-1 h-4 w-4 stroke-current"
												><path
													d="M6.75 5.75 9.25 8l-2.5 2.25"
													stroke-width="1.5"
													stroke-linecap="round"
													stroke-linejoin="round"
												/></svg
											>
										</div>
									</article>
								</div>
								<div class="space-y-10 lg:pl-16 xl:pl-24">
									<div class="rounded-2xl border border-zinc-100 p-6 dark:border-zinc-700/40">
										<h2 class="flex text-sm font-semibold text-zinc-900 dark:text-zinc-100">
											<svg
												viewBox="0 0 24 24"
												fill="none"
												stroke-width="1.5"
												stroke-linecap="round"
												stroke-linejoin="round"
												aria-hidden="true"
												class="h-6 w-6 flex-none"
												><path
													d="M2.75 9.75a3 3 0 0 1 3-3h12.5a3 3 0 0 1 3 3v8.5a3 3 0 0 1-3 3H5.75a3 3 0 0 1-3-3v-8.5Z"
													class="fill-zinc-100 stroke-zinc-400 dark:fill-zinc-100/10 dark:stroke-zinc-500"
												/><path
													d="M3 14.25h6.249c.484 0 .952-.002 1.316.319l.777.682a.996.996 0 0 0 1.316 0l.777-.682c.364-.32.832-.319 1.316-.319H21M8.75 6.5V4.75a2 2 0 0 1 2-2h2.5a2 2 0 0 1 2 2V6.5"
													class="stroke-zinc-400 dark:stroke-zinc-500"
												/></svg
											><span class="ml-3">Work</span>
										</h2>
										<ol class="mt-6 space-y-4">
											<li class="flex gap-4">
												<div
													class="bg-zinc-800 relative mt-1 flex h-10 w-10 flex-none items-center justify-center rounded-full shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
												>
													<img
														alt=""
														loading="lazy"
														width="32"
														height="32"
														decoding="async"
														data-nimg="1"
														class="h-7 w-7"
														src="images/build.svg"
													/>
												</div>
												<dl class="flex flex-auto flex-wrap gap-x-2">
													<dt class="sr-only">Company</dt>
													<dd
														class="w-full flex-none text-sm font-medium text-zinc-900 dark:text-zinc-100"
													>
														Weber County Utah
													</dd>
													<dt class="sr-only">Role</dt>
													<dd class="text-xs text-zinc-500 dark:text-zinc-400">
														Web Developer Intern
													</dd>
													<dt class="sr-only">Date</dt>
													<dd
														class="ml-auto text-xs text-zinc-400 dark:text-zinc-500"
														aria-label="2019 until Present"
													>
														<time datetime="2019">2022</time> <span aria-hidden="true">—</span>
														<time datetime="2023">Present</time>
													</dd>
												</dl>
											</li>
											<li class="flex gap-4">
												<div
													class="bg-zinc-800 relative mt-1 flex h-10 w-10 flex-none items-center justify-center rounded-full shadow-md shadow-zinc-800/5 ring-1 ring-zinc-900/5 dark:border dark:border-zinc-700/50 dark:bg-zinc-800 dark:ring-0"
												>
													<img
														alt=""
														loading="lazy"
														width="28"
														height="28"
														decoding="async"
														data-nimg="1"
														class="h-7 w-7"
														style="color:transparent"
														src="images/mail.svg"
													/>
												</div>
												<dl class="flex flex-auto flex-wrap gap-x-2">
													<dt class="sr-only">Company</dt>
													<dd
														class="w-full flex-none text-sm font-medium text-zinc-900 dark:text-zinc-100"
													>
														United States Postal Service
													</dd>
													<dt class="sr-only">Role</dt>
													<dd class="text-xs text-zinc-500 dark:text-zinc-400">
														Data Conversion Operator
													</dd>
													<dt class="sr-only">Date</dt>
													<dd
														class="ml-auto text-xs text-zinc-400 dark:text-zinc-500"
														aria-label="2014 until 2019"
													>
														<time datetime="2014">2015</time> <span aria-hidden="true">—</span>
														<time datetime="2019">2022</time>
													</dd>
												</dl>
											</li>
										</ol>
									</div>
								</div>
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
