# YNOproject Yume2kki 开关状态 检查

🚧**该脚本尚在开发中**🚧

[更新日志](https://github.com/Exsper/yno2kkiswitchcheck/blob/master/Changelog.md)

本工具通过遍历游戏内存数据来筛选开关的地址，实时显示开关的值。

使用本工具会改变原有的游戏体验，推荐对游戏有深入了解后再使用。

**本工具仅读取游戏内存，不会对游戏内容、内存或存档作任何修改。**

## 原理

检索内存（HEAPU8）

通过反复检索效果状态来定位相关开关的地址

## 使用方法

将脚本添加到Tampermonkey中

浏览器打开游戏页面，右侧会出现“+”按钮，点开即可打开脚本面板，点击右上方“-”按钮可以隐藏面板

按脚本界面的提示操作进行开关检索
