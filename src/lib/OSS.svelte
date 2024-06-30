<script lang="ts">
	import * as Accordion from '$lib/components/ui/accordion';
	import { ChevronRight } from 'lucide-svelte';
</script>

<div class="mx-auto max-w-[85rem] px-4 sm:px-6 lg:px-8 lg:py-10">
	<!-- Title -->
	<h2 class="text-center text-2xl font-bold sm:mb-12 sm:text-3xl">
		Built using open source technologies
	</h2>
	<!-- Icon Blocks -->
	<div class="mx-auto max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-1">
		<div class="grid items-center gap-6 sm:grid-cols-2 lg:grid-cols-3">
			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://tauri.app/"
			>
				<img
					src="/oss/tauri-1.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Tauri</h3>
						<p class="">
							Build an optimized, secure, and frontend-independent application for multi-platform
							deployment.
						</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://svelte.dev/"
			>
				<img
					src="/oss/svelte-1.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Svelte</h3>
						<p class="">
							Cybernetically enhanced web apps. Compiled, compact and the complete JS framework
						</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://www.rust-lang.org/"
			>
				<img
					src="/oss/rust.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Rust</h3>
						<p class="">A language empowering everyone to build reliable and efficient software.</p>
					</div>
				</div>
			</a>
			<!-- End Card -->
		</div>
	</div>
	<div class="mx-auto max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-1">
		<div class="grid items-center gap-6 sm:grid-cols-2 lg:grid-cols-3">
			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://codemirror.net/"
			>
				<img
					src="/oss/codemirror.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">CodeMirror</h3>
						<p class="">
							A code editor component that supports many editing features, has a rich interface to
							allow further extension.
						</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://quobix.com/vacuum/about/"
			>
				<img
					src="/oss/vacuum.png"
					class="me-6 mt-0.5 h-10 w-12 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Vacuum</h3>
						<p class="">
							vacuum is an ultra-super-fast, lightweight OpenAPI linter and quality checking tool,
							inspired by Spectral.
						</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://quilljs.com/"
			>
				<img
					src="/oss/quill.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Quilljs</h3>
						<p class="">An API Driven and powerful rich text editor.</p>
					</div>
				</div>
			</a>
			<!-- End Card -->
		</div>
	</div>
	<div class="mx-auto max-w-[85rem] px-4 py-10 sm:px-6 lg:px-8 lg:py-1">
		<div class="grid items-center gap-6 sm:grid-cols-2 lg:grid-cols-3">
			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://tailwindcss.com/"
			>
				<img
					src="/oss/tailwindcss.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Tailwind</h3>
						<p class="">Rapidly build modern websites without ever leaving your HTML.</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://scalar.com/"
			>
				<img
					src="/oss/scalar.svg"
					class="me-6 mt-0.5 h-10 w-12 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Scalar</h3>
						<p class="">Scalar builds open-source tools, with first class OpenAPI support.</p>
					</div>
				</div>
			</a>
			<!-- End Card -->

			<!-- Card -->
			<a
				class="group flex size-full gap-y-6 rounded-lg p-5 transition-all hover:bg-gray-100 dark:hover:bg-neutral-800 dark:focus:bg-neutral-800 dark:focus:outline-none dark:focus:outline-none"
				href="https://www.shadcn-svelte.com/"
			>
				<img
					src="/oss/shad.svg"
					class="me-6 mt-0.5 size-8 flex-shrink-0 text-gray-800 dark:text-neutral-200"
					alt=""
					srcset=""
				/>

				<div>
					<div>
						<h3 class="block font-bold text-gray-800 dark:text-white">Shadcn-Svelte</h3>
						<p class="">
							Beautifully designed components that you can copy and paste into your apps.
						</p>
					</div>
				</div>
			</a>
			<!-- End Card -->
		</div>
	</div>
	<!-- End Icon Blocks -->
</div>
