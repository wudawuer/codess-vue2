## 3useinoptions
#### Use Composition API within Options API
Use Composition API within Options API
```
import { ${0:component} } from '@/composables/${0:component}.js'

export default {
	setup () {
		const { ${1:name} } = ${0:component}()
	
		return {
			${1:name}
		}
	}
}
```