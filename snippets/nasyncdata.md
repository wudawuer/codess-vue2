## nasyncdata
#### Nuxt Async
Nuxt asyncData
```
async asyncData ({ ${1:params} }) {
	const { data } = await fetch(`${2:endpoint}`).then(res => res.json())
	return { ${3:key}:${4:value} }
},
```