## mapstate
#### Vue MapState
map getters inside a vue component
```
import { mapState } from 'vuex';

export default {
	computed: {
		...mapState([
			${1:'nameOfState'},
		])
	},
};
```