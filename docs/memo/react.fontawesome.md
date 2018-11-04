
# how to use

```js
// Font Awesome
import { FontAwesomeIcon } from '@fortawesome/react-fontawesome'
import { library } from '@fortawesome/fontawesome-svg-core'
import { faCoffee, faStroopwafel } from '@fortawesome/free-solid-svg-icons'

library.add(faCoffee, faStroopwafel);
```

```html
<div>stroopwafel: <FontAwesomeIcon icon="stroopwafel" /></div>
<div>coffee: <FontAwesomeIcon icon="coffee" /></div>
```
