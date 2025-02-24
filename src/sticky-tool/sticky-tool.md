:: BASE_DOC ::

## API

### StickyTool Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
collapsed | Boolean | false | 默认是否折叠 | N
draggable | Boolean | false | 是否可拖拽 | N
entrance | TElement | - | 自定义折叠入口，collapsed 值为 true 有效。TS 类型：`TNode`。[通用类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/common.ts) | N
list | Array | [] | 列表。TS 类型：`Array<TdStickyItemProps>` | N
offset | Object | - | 相对于 placement 的偏移量，示例：[-10, 20] 或 ['10em', '8rem']。TS 类型：<code>Array&lt;string &#124; number&gt;</code> | N
placement | String | right-bottom | 固定位置。可选项：right-top/right-center/right-bottom/left-top/left-center/left-bottom | N
width | String / Number | - | 宽度 | N
onClick | Function |  | 点击某一项时触发。`(context: { e: MouseEvent; item: TdStickyItemProps }) => {}` | N
onHover | Function |  | 悬浮到某一项时触发。`(context: { e: MouseEvent; item: TdStickyItemProps }) => {}` | N

### StickyItem Props

名称 | 类型 | 默认值 | 说明 | 必传
-- | -- | -- | -- | --
icon | TNode | - | 图标。TS 类型：<code>string &#124; TNode</code>。[通用类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/common.ts) | N
label | TNode | - | 名称。TS 类型：<code>string &#124; TNode</code>。[通用类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/common.ts) | N
popup | TNode | - | 浮层内容。TS 类型：<code>string &#124; TNode</code>。[通用类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/common.ts) | N
popupProps | Object | - | 透传浮层组件全部属性。TS 类型：`PopupProps`。[详细类型定义](https://github.com/Tencent/tdesign-react/blob/main/src/sticky-tool/type.ts) | N
trigger | String | hover | 触发浮层显示的方式。可选项：hover/click | N
