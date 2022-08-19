### d-async-validate-regexp

#### 使用方法

##### step1：安装

```js
// npm安装
npm install d-async-validate-regexp

// yarn安装
yarn add d-async-validate-regexp

// pnpm安装
pnpm add d-async-validate-regexp
```

##### step2：使用

```js
import { number } from 'd-async-validate-regexp'

number('1111')
```

#### 方法

方法运行的返回值是true和false。

| 方法名称    | 说明                       | 参数（类型）                                                 |
| ----------- | -------------------------- | ------------------------------------------------------------ |
| email       | 验证电子邮箱格式           | value: string                                                |
| mobile      | 验证手机格式               | value: string                                                |
| url         | 验证URL格式                | value: string                                                |
| date        | 验证日期格式               | value: string / number                                       |
| dateISO     | 验证ISO类型的日期格式      | value: string                                                |
| number      | 验证十进制数字             | value: string / number                                       |
| string      | 验证字符串                 | value: string                                                |
| digits      | 验证整数                   | value: string / number                                       |
| idCard      | 验证身份证号码             | value: string / number                                       |
| carNo       | 是否车牌号                 | value: string / number                                       |
| amount      | 金额,只允许2位小数         | value: string / number                                       |
| chinese     | 中文                       | value: string                                                |
| letter      | 只能输入字母               | value: string                                                |
| enOrNum     | 只能是字母或者数字         | value: string                                                |
| contains    | 验证是否包含某个值         | value: string，param: string                                 |
| range       | 验证一个值范围[min, max]   | value: string / number，param: [string / number, string / number] |
| rangeLength | 验证一个长度范围[min, max] | value: string, param: [string / number, string / number]     |
| landline    | 是否固定电话               | value: string / number                                       |
| empty       | 判断是否为空               | value: any                                                   |
| jsonString  | 是否json字符串             | value: string                                                |
| array       | 是否数组                   | value: any                                                   |
| object      | 是否对象                   | value: any                                                   |
| code        | 是否短信验证码             | value: string / number, len: number(默认值是6)               |
| func        | 是否函数方法               | value: object                                                |
| promise     | 是否promise对象            | value: object                                                |
| image       | 是否图片格式               | value: object                                                |
| video       | 是否视频格式               | value: object                                                |
| regExp      | 是否为正则对象             | value: object                                                |

