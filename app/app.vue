<template>
	<UApp>
		<NuxtLayout>
			<NuxtPage />
		</NuxtLayout>
	</UApp>
</template>

<script setup>
useHead({
	title: 'WuWa Planner : Wuthering Waves Planner',
	meta: [
		{
			name: 'description',
			content: 'WuWa Planner : Wuthering Waves Planner',
		},
	],

	link: [
		{
			rel: 'icon',
			type: 'image/x-icon',
			href: useRuntimeConfig().app.baseURL + 'favicon.ico',
		},
	],
});
</script>
