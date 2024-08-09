## 3reactive-setup
#### Vue Composition API Reactive Script
Vue Composition API Script with Reactive
```
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
```