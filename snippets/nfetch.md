## nfetch
#### Nuxt Fetch
Nuxt Fetch
```
async fetch ({ store, ${1:params} }) {
	let { data } = await fetch('${2:endpoint}').then(res => res.json())
	store.commit('${3:MUTATION_TYPE}', data)
},
```