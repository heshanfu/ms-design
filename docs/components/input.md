---
title: Input 输入框
---

<ClientOnly>
  <input-page />
</ClientOnly>

### API

#### Input props
| 属性 | 说明 | 类型 | 可选值 | 默认值 |
| :------------ | :------------ | :------------ | :------------ | :------------ |
| type | 输入框类型 | String | `text`、`password` 或者不设置 | `text` |
| disabled | 输入框是否禁用 | Boolean | `true` \| `false` | `false` |

#### Input event
| 事件名 | 说明 | 返回值 |
| :------------ | :------------ | :------------ |
| input | 输入框内容改变时触发 | 改变后的内容 |
| focus | 输入框聚焦时触发 | 无 |
| blur | 输入框失去焦点时触发 | 无 |