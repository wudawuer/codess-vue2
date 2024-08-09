## mapactions
#### Vue MapActions
mapactions inside a vue component
```
import { mapActions } from 'vuex';

export default {
	methods: {
		...mapActions([
			${1:'nameOfAction'}, //also supports payload `this.nameOfAction(amount)` 
		])
	},
};
```