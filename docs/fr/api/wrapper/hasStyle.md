# hasStyle(style, value)

<p><strong>⚠Cette page est actuellement en cours de traduction française. Vous pouvez repasser plus tard ou <a href="https://github.com/vuejs-fr/vue-test-utils" target="_blank">participer à la traduction</a> de celle-ci dès maintenant !</strong></p><p>Assert `Wrapper` DOM node has style matching value.</p>

Returns `true` if `Wrapper` DOM node has `style` matching `value`.

**Note will only detect inline styles when running in `jsdom`.**

- **Arguments:**
  - `{string} style`
  - `{string} value`

- **Returns:** `{boolean}`

- **Example:**

```js
import { mount } from '@vue/test-utils'
import { expect } from 'chai'
import Foo from './Foo.vue'

const wrapper = mount(Foo)
expect(wrapper.hasStyle('color', 'red')).toBe(true)
```
