## base-3-reactive
#### Vue Single File Component Composition API Reactive
Base for Vue File Composition API with SCSS
```
<template>
	<div>

	</div>
</template>

<script>
import { reactive, toRefs } from 'vue'

export default {
	setup () {
		const state = reactive({
			${0:count}: ${1:0},
		})
	
		return {
			...toRefs(state),
		}
	}
}
</script>

<style lang="scss" scoped>

</style>
```