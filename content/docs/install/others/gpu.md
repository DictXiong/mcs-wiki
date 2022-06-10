---
title: "双显卡"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# 双显卡配置

如果使用笔记本电脑，有双显卡，那么需要手动配置令Java使用独立显卡。

请在你的**显卡配置面板**中调整此设置。以NVIDIA显卡为例：

- 右键桌面 – NVIDIA 控制面板 – 管理3D设置 – 程序设置
- “选择要自定义的程序”的下拉框中寻找你所使用的 `java.exe` 和 `javac.exe`; 如果没有，则点击右侧“添加”按钮手动添加 `java.exe` 及 `javac.exe`.
- 分别配置为“高性能”.

