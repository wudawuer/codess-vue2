## animhook-js
#### Vue Transition Methods with JavaScript Hooks
transition component js hooks
```
beforeEnter(el) {
	console.log('beforeEnter');
},
enter(el, done) {
	console.log('enter');
	done();
},
beforeLeave(el) {
	console.log('beforeLeave');
},
leave(el, done) {
	console.log('leave');
	done();
},
```