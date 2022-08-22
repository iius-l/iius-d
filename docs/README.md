# 简介

收集常用的，使用的工具，辅助函数。

与 lodash、radam 等工具函数库类似，但又不大相同。

不为重复造轮子，只为解决问题，提高开发效率。



## 安装

```shell
npm install iius
```

你也可以使用 `yarn` `pnpm` `cnpm` 等 package 管理工具



## 使用

### CJS

```javascript
const iius = require('iius')
```



### ESM

```typescript
import { fp } from 'iius'
// 或者
import * as iius from 'iius'
```



### 浏览器

```html
<script src="https://unpkg.com/iius@version/iius.min.js"></script>
```

关于版本可以查看 [npmjs](https://www.npmjs.com/package/iius)，或者直接使用 [最新版](https://unpkg.com/iius@latest)



## 文档

对于每个函数，尽量都会带上源码地址，demo 地址（如果有的话），例子。



## 支持

- 支持 **CommonJs**、**ESModule** 两大模块系统
- 支持 **ESModule  Tree Shaking**
- 支持 **TypeScript**



## 贡献

希望有幸看到该库的人们，可以贡献一下你们常用的工具函数，集成到当中去。也希望你们在提供之前，先做好相关的测试工作 😁