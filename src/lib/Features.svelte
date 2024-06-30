<script>
	import { Bug, Ruler, Component, BadgeCheck, Sparkle, Gem, Star } from 'lucide-svelte';
</script>

<div class="mx-auto max-w-[85rem] px-4 pt-10 sm:px-6 lg:px-8">
	<h2 class="mb-6 text-center text-2xl font-bold sm:mb-12 sm:text-3xl">What Frogment Can do</h2>
	<div class="grid grid-cols-2 gap-4 py-10">
		<div
			class="h-96 w-full rounded-xl border border-black bg-[url('/w_edit-min.png')] bg-cover bg-left-top bg-no-repeat object-cover shadow-xl sm:h-[480px]"
		></div>
		<div class="pl-8">
			<div
				class="mb-2 inline-block rounded-md border-2 border-primary bg-gradient-to-r from-violet-200 to-pink-200 p-2"
			>
				<BadgeCheck class="text-primary-500 h-8 w-8" />
			</div>
			<h3 class="mb-3 text-2xl font-semibold">A Complete IDE</h3>
			<p class="text-primary">
				Frogment aims to give a vscode like Experience while editing your OpenAPI specification.
			</p>
			<ul class="mt-4 list-none">
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Full fledged editor powered by CodeMirror 6
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Auto-completion
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Click to follow component references
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					A complete search experience
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Dark and Light Mode
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Quick Open
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Keyboard Shortcuts
				</li>
				<li class="my-4 font-medium">
					<BadgeCheck class="inline-block h-4 w-4 stroke-indigo-500 text-green-500" />
					Easily add new paths and components
				</li>
				<!-- ... -->
			</ul>
		</div>
		<!-- ... -->
	</div>
	<div class="grid grid-cols-2 gap-4 py-20">
		<div class="pr-8">
			<div
				class="mb-2 inline-block rounded-md border-2 border-primary bg-gradient-to-r from-violet-200 to-pink-200 p-2"
			>
				<Bug class="text-primary-500 h-8 w-8" />
			</div>
			<h3 class="mb-3 text-2xl font-semibold">Built-in linter</h3>
			<p class="text-primary">
				Lint your code with Frogment's built-in linter with predefined rules powered by <a
					class="text-blue-500"
					href="https://quobix.com/vacuum/about/">vacuum:</a
				>
				a <strong>ultra-super-fast</strong>, lightweight
				<a class="text-blue-500" href="https://www.openapis.org/">OpenAPI</a>
				linter and quality checking tool, inspired by
				<a class="text-blue-500" href="https://github.com/stoplightio/spectral">Spectral</a>
			</p>
			<ul class="mt-4 list-none">
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					Supports rules for OpenAPI 3.0.0 and 3.1.0
				</li>
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					Find and fix problems in your specification
				</li>
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					Pre configured <a class="text-blue-500" href="https://quobix.com/vacuum/rules/">rules</a>
				</li>
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					Toggle between different rule sets
				</li>
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					View Report in the editor or as HTML
				</li>
				<li class="my-4 font-medium">
					<Sparkle class="inline-block h-4 w-4 stroke-yellow-500  " />
					Detailed statistics for your specification
				</li>
				<!-- ... -->
			</ul>
		</div>
		<!-- ... -->
		<div
			class="bg-200% h-96 w-full rounded-xl border border-black bg-[url('/w_lint-min.png')] bg-left-bottom bg-no-repeat object-cover shadow-xl sm:h-[480px]"
		></div>
	</div>

	<!-- Two -->
	<div class="grid grid-cols-2 gap-4 py-20">
		<div
			class="h-96 w-full rounded-xl border border-black bg-[url('/w_cat-min.png')] bg-cover bg-left-top bg-no-repeat object-cover shadow-xl sm:h-[480px]"
		></div>
		<div class="pl-8">
			<div
				class="mb-2 inline-block rounded-md border border-primary bg-gradient-to-r from-violet-200 to-pink-200 p-2"
			>
				<Ruler class="text-primary-500  h-8 w-8" />
			</div>
			<h3 class="mb-3 text-2xl font-semibold">Integrated wysiwyg</h3>
			<p class="text-primary">
				Edit the description of your schemas and path using Frogment's integrated wysiwyg editor.
			</p>
			<ul class="mt-4 list-none">
				<li class="my-4 font-medium">
					<Gem class="mr-2 inline-block h-4 w-4  stroke-orange-500" />
					Add tables, links and images to your documentation with ease.
				</li>
				<li class="my-4 font-medium">
					<Gem class="mr-2 inline-block h-4 w-4  stroke-orange-500" />
					Full featured wysiwyg editor for description
				</li>
				<li class="my-4 font-medium">
					<Gem class="mr-2 inline-block h-4 w-4  stroke-orange-500" />
					Color and font customization
				</li>
				<li class="my-4 font-medium">
					<Gem class="mr-2 inline-block h-4 w-4  stroke-orange-500" />
					Supports preview of your specification using
					<a class="text-blue-500" href="https://github.com/scalar/scalar">scalar</a>
				</li>

				<!-- ... -->
			</ul>
		</div>
		<!-- ... -->
	</div>
</div>
