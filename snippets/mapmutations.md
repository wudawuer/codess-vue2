## mapmutations
#### Vue MapMutations
mapmutations inside a vue component
```
import { mapMutations } from 'vuex';

export default {
	methods: {
		...mapMutations([
			${1:'nameOfMutation'}, //also supports payload `this.nameOfMutation(amount)` 
		])
	},
};
```