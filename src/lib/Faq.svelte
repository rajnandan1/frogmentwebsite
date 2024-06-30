<script lang="ts">
	import * as Accordion from '$lib/components/ui/accordion';
</script>

<div class="mx-auto max-w-[45rem] px-4 sm:px-6 lg:px-8 lg:py-10">
	<!-- Title -->
	<h2 class="text-center text-2xl font-bold sm:mb-12 sm:text-3xl">Frequent Asked Questions</h2>
	<Accordion.Root>
		<Accordion.Item value="item-1">
			<Accordion.Trigger>Why do I get a security warning on mac?</Accordion.Trigger>
			<Accordion.Content>
				I am yet to get the app notorized for which I have to pay $99 to apple. For now you can go
				to System Settings > Privacy > Open Anyway.
			</Accordion.Content>
		</Accordion.Item>
		<Accordion.Item value="item-2">
			<Accordion.Trigger>Which Versions of OpenAPI does it support?</Accordion.Trigger>
			<Accordion.Content>It supports all the versions of OpenAPI.</Accordion.Content>
		</Accordion.Item>
		<Accordion.Item value="item-3">
			<Accordion.Trigger>Why is it not available for Windows?</Accordion.Trigger>
			<Accordion.Content
				>I don't have a windows laptop. It will come at some point, just not today</Accordion.Content
			>
		</Accordion.Item>
		<Accordion.Item value="item-4">
			<Accordion.Trigger>How do I raise a bug or request a feature?</Accordion.Trigger>
			<Accordion.Content>
				You can raise a bug by going to the <a
					class="text-blue-500"
					href="https://github.com/rajnandan1/frogmentwebsite/issues">issues</a
				> tab on the github repository.
			</Accordion.Content>
		</Accordion.Item>
	</Accordion.Root>
</div>
