## c-direct
#### Vue Custom Directive
vue custom directive
```
Vue.directive('${1:directiveName}', {
	bind(el, binding, vnode) {
		el.style.${2:arg} = binding.value.${2:arg};
	}
});
```