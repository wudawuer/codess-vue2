## store2
#### Vuex Store 2
vuex store 2
```
export const state = () => ({
	value: 'myvalue'
})

export const getters = {
	getterValue: state => {
		return state.value
	}
}

export const mutations = {
	updateValue: (state, payload) => {
		state.value = payload
	}
}

export const actions = {
	updateActionValue({ commit }) {
		commit('updateValue', payload)
	}
}
```