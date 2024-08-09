## mapgetters
#### Vue MapGetters
mapgetters inside a vue component
```
import { mapGetters } from 'vuex';

export default {
	computed: {
		...mapGetters([
			${1:'nameOfGetter'},
		])
	},
};
```