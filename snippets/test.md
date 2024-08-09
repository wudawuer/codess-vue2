## test
#### Unit Test
unit test component
```
import Vue from 'vue';
import ${1:HelloWorld} from './components/${1:HelloWorld}';

describe('${1:HelloWorld}.vue', () => {
	it('${2:should render correct contents}', () => {
		const Constructor = Vue.extend(${1:HelloWorld});
		const vm = new Constructor().$mount();
		expect(vm.$el.querySelector('.hello h1').textContent)
			.to.equal(${3:'Welcome to Your Vue.js App'});
	});
});
```