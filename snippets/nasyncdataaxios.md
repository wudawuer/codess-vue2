## nasyncdataaxios
#### Nuxt Async 2
Nuxt asyncData with Axios module
```
async asyncData ({ ${1:$axios}, { ${2:params} }) {
	const data = await $axios.$get(`${3:endpoint/${params.slug}}`)
	return { data }
},
```