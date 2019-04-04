<template>
	<div>
		Home Vue Components

		<input type="text" v-model="text" class="form-control" placeholder="text..">

		{{ text }}

		<br>

		<home-link :list="list"></home-link>
	</div>
</template>

<script>
import HomeLink from './HomeLink.vue'
export default {
	components: {
		HomeLink
	},

	data () {
		return {
			text: '',
			list: [
				'a',
				'b',
				'c',
				'd'
			]
		}
	}
}
</script>
