<script lang="ts">
	import { TypewriterEffectSmooth, TypewriterEffect } from '$lib/components/ui/TypewriterEffect';
	import { CardContainer, CardBody, CardItem } from '$lib/components/ui/ThreeDCardEffect';
	import { TextGenerateEffect } from '$lib/components/ui/TextGenerateEffect';
	import { text } from '@sveltejs/kit';
	import { animate } from 'motion';
	import { onMount } from 'svelte';
	const heading = [
		{
			text: 'HI'
		},
		{
			text: 'IM'
		},
		{
			text: 'DOM.'
		}
	];

	const subText = 'plan. design. create.';
	const shortBio = `"I like creating functional and
well-designed applications, dabbling with design, functionality, and databases."`;

	let isMouseEntered = false;

	onMount(() => {
		// animate('.HEADING', { x: '200px' }, { duration: 1 });
	});
</script>

<div
	class="mx-auto flex max-w-4xl flex-col items-center justify-center gap-4 p-4 leading-3 outline-1"
>
	<!-- <h1 class="HEADING flex-initial text-6xl font-extrabold tracking-normal md:text-8xl">About</h1> -->

	<h1
		class="HEADING mt-4 flex-initial text-center text-3xl font-extrabold tracking-normal md:text-7xl"
	>
		About
	</h1>

	<div class="flex flex-initial flex-col gap-8 p-4">
		<p class="text-center text-lg font-medium tracking-wide md:text-3xl">
			As a web developer, I find learning about web technologies to be fun, challenging, and
			rewarding.
		</p>

		<p class="text-center text-lg font-medium tracking-wide md:text-3xl">
			Currently, I'm in my third year of college pursuing a Bachelor's degree in Information
			Technology.
		</p>
	</div>
</div>
