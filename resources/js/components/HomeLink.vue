<template>
	<div>
		<ul>
			<li v-for="(i, index) in list" :key="index">{{ i }} {{ index }}</li>
		</ul>
	</div>
</template>

<script>
export default {
	props: ['list']
}
</script>
