## config
#### Vue.config.js Import
vue.config.js
```
module.exports = {
	css: {
		loaderOptions: {
			${1:sass}: {
				data: `${2:@import '@/styles/_variables.scss';}`
			}
		}
	}
}
```