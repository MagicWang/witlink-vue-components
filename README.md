## @witlink/components 库介绍

> Witlink 公共组件库，仅包含与业务无关的组件、指令、勾子、工具方法等。持续完善中。。。

- 📖 [**帮助文档**](https://witlink.cloud/docs/](https://magicwang.github.io/witlink-vue-components/)

### 如何使用@witlink/components

##### 1. 安装@witlink/components

```bash
npm install @witlink/components
```

##### 2. 使用@witlink/components

- 全局引入

```js
import WitlinkComponents from "@witlink/components";

const app = createApp(App);
app.use(WitlinkComponents);
```

- 按需引入

```js
import {
  WlSplitter,
  permission,
  useComponentRef,
  isNullOrUndef,
  exportFile,
} from "@witlink/components";
```

- 工具类方法也可以从 utils 目录引入

```js
import { isNullOrUndef, exportFile } from "@witlink/components/utils";
```
