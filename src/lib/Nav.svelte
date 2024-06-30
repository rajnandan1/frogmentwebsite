<script>
	let hidden = true;
	import { Menu } from 'lucide-svelte';
</script>

<header class="sticky inset-x-0 top-4 z-50 flex w-full flex-wrap md:flex-nowrap md:justify-start">
	<nav
		class="relative mx-2 w-full max-w-[66rem] rounded-[28px] bg-gradient-to-r from-slate-500 to-slate-800 py-3 pe-2 ps-2 md:flex md:items-center md:justify-between md:py-0 lg:mx-auto"
		aria-label="Global"
	>
		<div class="flex items-center justify-between">
			<!-- Logo -->
			<a
				class="inline-block flex-none rounded-md text-xl font-semibold text-white focus:opacity-80 focus:outline-none"
				href="../templates/agency/index.html"
				aria-label="Preline"
			>
				<img src="/icons/Square107x107Logo.png" alt="" class="inline-block h-10" />
				FROGMENT
			</a>
			<!-- End Logo -->

			<div class="md:hidden">
				<button
					on:click={() => (hidden = !hidden)}
					type="button"
					class="hs-collapse-toggle flex size-8 items-center justify-center rounded-full bg-green-200 text-sm font-semibold text-white disabled:pointer-events-none disabled:opacity-50"
					data-hs-collapse="#navbar-collapse"
					aria-controls="navbar-collapse"
					aria-label="Toggle navigation"
				>
					<Menu class="size-4 text-primary" />
				</button>
			</div>
		</div>

		<!-- Collapse -->
		<div
			id="navbar-collapse"
			class="hs-collapse {hidden
				? 'hidden'
				: ''} grow basis-full overflow-hidden transition-all duration-300 md:block"
		>
			<div class="flex flex-col py-2 md:flex-row md:items-center md:justify-end md:py-0 md:ps-7">
				<a
					href="https://github.com/sponsors/rajnandan1"
					class="cursor-pointer py-3 ps-px text-sm font-medium text-white hover:text-neutral-300 focus:text-neutral-300 focus:outline-none sm:px-3 md:py-4"
				>
					DONATE
				</a>

				<div>
					<a
						class="group inline-flex w-full items-center gap-x-2 rounded-full bg-[#75fbb2] px-3 py-2 text-sm font-medium text-neutral-800 focus:outline-none md:w-auto"
						href="../templates/agency/index.html#contact"
					>
						<img src="/apple-logo-svgrepo-com.svg" alt="" class="inline-block h-6" />
						Download for Mac
					</a>
				</div>
			</div>
		</div>

		<!-- End Collapse -->
	</nav>
</header>
