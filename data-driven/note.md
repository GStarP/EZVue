## 数据更新到 DOM 更新

- 先将 AST 和 data 结合生成新的 VNode (render)
- 将旧的 VNode 和 新的 VNode 进行比较 (diff)
- 更新 DOM (update)

![](../imgs/data-vnode-dom.png)
