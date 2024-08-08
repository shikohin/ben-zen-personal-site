<template>
	<div><PostCard :posts="posts" /></div>
</template>

<script setup lang="ts">
	const posts = [
		{
			id: 1,
			title: 'Post 1',
			date: 'Tuesday, August 8,',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: 'headshot.jpg'
		},
		{
			id: 2,
			title: 'Post 2',
			date: '',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 3,
			title: 'Post 3',
			date: '',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 4,
			title: 'A More Involved Post Title',
			date: '',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 5,
			title: 'newPost-5',
			date: '',
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 6,
			title: 'newPost-6',
			date: Date.now(),
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 7,
			title: 'newPost-7',
			date: Date.now(),
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 8,
			title: 'newPost-8',
			date: Date.now(),
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 9,
			title: 'newPost-9',
			date: Date.now(),
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
		{
			id: 10,
			title: 'newPost-10',
			date: Date.now(),
			content: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia doloribus in officiis laudantium natus. Autem, hic laboriosam, excepturi laudantium sunt tempore laborum qui, alias magnam cum ab ipsam in iure?',
			img: ''
		},
	]


</script>
