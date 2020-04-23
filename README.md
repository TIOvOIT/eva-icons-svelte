_组件基于[component-template](https://github.com/sveltejs/component-template)构建_

---

# 简介

使用 Svelte 对 Eva icons 简单封装的组件。

# 预览

[DEMO](https://svelte.dev/repl/9660e216a02c409ea54f24b769748347)

[官方介绍](https://akveo.github.io/eva-icons/#/)

# 安装

```bash

npm i eva-icons-svelte
```

# 使用

```javascript
import { IconActivity } from "eva-icons-svelte";
```

```html
<IconActivity />
```

请使用大驼峰命名法，并前面加上 Icon 来贴合语义，例如:

`github` 的组件名为 `IconGithub`；
`arrow-left` 的组件名为 `IconArrowLeft`；
`bar-chart-2-outline` 的组件名为 `IconBarChar2`。

由于 `outline` 和 `fill` 都封装成了一个组件，所以请务必忽略名称中的 `outline`。

如果想添加样式，请添加给其父级标签。例如：
给父级 css 样式 `fill:green;` 以更换图标颜色。

## API

|   API   | 类型   | 参数                            | 描述                                                                 |
| :-----: | ------ | ------------------------------- | -------------------------------------------------------------------- |
| pattern | string | outline or fill ,默认为 outline | 显示模式：`outline` 线框或 `fill` 正负形，部分图标两种模式下图案相同 |

## License

MIT
