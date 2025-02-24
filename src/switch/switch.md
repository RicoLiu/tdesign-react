:: BASE_DOC ::

## API

### Switch Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
customValue | Array | - | 开关内容，[打开时的值，关闭时的值]。默认为 [true, false]。示例：[1, 0]。TS 类型：`Array<SwitchValue>` | N
disabled | Boolean | false | 是否禁用组件 | N
label | TNode | [] | 开关内容，[开启时内容，关闭时内容]。示例：['开', '关'] 或 (value) => value ? '开' : '关'。TS 类型：<code>Array&lt;string &#124; TNode&gt; &#124; TNode&lt;{ value: SwitchValue }&gt;</code>。[通用类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/common.ts) | N
loading | Boolean | false | 是否处于加载中状态 | N
size | String | medium | 开关尺寸。可选项：small/medium/large | N
value | String / Number / Boolean | false | 开关值。TS 类型：`SwitchValue`。[详细类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/switch/type.ts) | N
defaultValue | String / Number / Boolean | false | 开关值。非受控属性。TS 类型：`SwitchValue`。[详细类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/switch/type.ts) | N
onChange | Function |  | 数据发生变化时触发。`(value: SwitchValue) => {}` | N
