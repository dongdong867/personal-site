<template>
	<div class="pt-[5vh] snap-end snap-always">
		<div class="w-[50vw]">
			A webpage that introduce the basic of proverb analysis an four translators.
		</div>
		<div
			class="work-button"
			@mouseenter="hoverOnButton = !hoverOnButton"
			@mouseleave="hoverOnButton = !hoverOnButton"
		>
			<a
				href="https://dongdong867.github.io/Translator_Introduction/"
				target="_blank"
				class="flex place-items-baseline gap-x-[1vw]"
			>
				<div
					:class="[{ 'animate-[link-hover-bounce_1s_infinite]': hoverOnButton }]"
					class="text-3xl"
				>
					→
				</div>
				<div>Go Site</div>
			</a>
		</div>
	</div>
</template>

<script setup>
const hoverOnButton = ref(false)
</script>
