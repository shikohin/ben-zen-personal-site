<template>
	<UCard class="m-10" v-for="post in posts">
		<template #header>
			<NuxtLink :to="{ hash: `#${formatSlug(post.title)}` }">
				<h2 class="h-2">{{ post.title }}</h2>
			</NuxtLink>
    </template>
		<p>{{ post.content }}</p>
	</UCard>
</template>

<script setup lang="ts">
	const posts = [
		{
			id: 1,
			title: 'Post 1',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?'
		},
		{
			id: 2,
			title: 'Post 2',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?'
		},
		{
			id: 3,
			title: 'Post 3',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?'
		},
		{
			id: 4,
			title: 'A More Involved Post Title',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?'
		},
	]

	function formatSlug(postTitle: string): string {
		return postTitle.trim().toLowerCase().replace(/\s/g, '-')
	}
</script>
