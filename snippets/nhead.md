## nhead
#### Nuxt Head
Nuxt Head
```
head () {
	return {
		title: ${1:'Page Title'},
		meta: [
			// hid is used as unique identifier. Do not use `vmid` for it as it will not work
			{ hid: 'description', name: 'description', content: ${2:'My custom description'} }
		]
	}
},
```