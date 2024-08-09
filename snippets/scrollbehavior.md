## scrollbehavior
#### Vue Router scrollBehavior
Vue Router scrollBehavior
```
scrollBehavior(to, from, savedPosition) {
	if(savedPosition) {
		return savedPosition;
	} else {
		return { x: 0, y: 0 };
	}
},
```