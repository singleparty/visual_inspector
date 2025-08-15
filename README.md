## Visual Inspector
[ENGLISH](https://github.com/gp5251/visual_inspector/blob/master/README.en.md)

[插件地址](https://chrome.google.com/webstore/detail/visual-inspector%E5%89%8D%E7%AB%AF%E9%87%8D%E6%9E%84%20%E8%A7%86%E8%A7%89%E8%B5%B0%E6%9F%A5/jgimcbonbekgeahallgcmiibdidjeeim)

> 这款插件可以高效的帮助前端工程师页面重构，高度视觉还原，也方便设计师UI走查。前端工程师在重构阶段就能快速发现页面和视觉稿的差异，减少大量和设计师的沟通成本。

> 可以随意修改设计稿`大小`，`位置`，`透明度`，`混合模式`等，方便各种设计风格的UI对比。

> 如果你在做页面重构，实时功能可以很方便的在页面刷新后恢复到页面刷新之前的状态(如设计稿的大小，位置，透明度等)。

> 同时，如果不需要移动拉伸设计稿了，建议打开冻结功能，这样设计稿将不再响应鼠标事件，不能拉伸和拖拽，也不会影响页面本身的交互功能。

> 预置了常用命令的快捷键，更加方便的操作和比对

### 2.0.0 适配 Chrome 插件 Manifest V3

### 新版(1.3.9+)去掉了测量功能，如果需要请安装测量插件，如：[better ruler](https://chrome.google.com/webstore/detail/better-ruler/ilcnadaaninblgbekoaihdhoiecaflie),支持吸附测量。

### 快捷键:

- h 键: 显示和隐藏图片
- f 键: 显示和隐藏底部工具栏
- d 键: 冻结和解冻图片
- 数字键（0-9）：`设置图片透明度`。如：1秒内快速按下两次5，将设置图片55%的透明度。如果1秒内只按下了一次数字键，如5，一秒后将自动补0，即设置图片透明度为50%。
- 方向键：移动图片，一次移动1px。如果同时按下Shift键，将一次移动10px。
- 快速匹配
    - alt + 0 : 重置
    - alt + 1 : 原图大小
    - alt + 2 : 原图两倍
    - alt + 3 : 原图一半
    - alt + 4 : 窗口宽度

### Tips: 
- 如果快捷键不起作用，请检查当前页面焦点是否在其他页面控件内(eg.input, textarea...)？最简单的方法，点击设计稿，或者页面空白处再试一试：）
- 测量模式下，双击页面可以暂停辅助线跟随鼠标，再双击可恢复跟随。

