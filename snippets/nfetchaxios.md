## nfetchaxios
#### Nuxt Fetch with Axios
Nuxt Fetch with Axios module
```
async fetch () {
	let this.data = await this.$axios.$get('${1:endpoint/${this.$route.params.slug}}')
},
```