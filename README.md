# reg-check
常用正则表达式


```js
const reg = require('reg-check') 
or
import reg from 'reg-check'

console.log(reg.email.test('123@gmail.com')) // log true

email
number
isCN //是否是中文
url
pwd //6-20个字符，必须同时包含大、小写字母及数字，不可包含特殊字符
phone //手机号码
```