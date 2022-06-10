---
title: "1. Java下载与配置"
weight: 2
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Java下载与配置

Java是运行Minecraft及各种启动器的基础。较新的Minecraft版本要求使用较新的Java，以下是一个大致对应列表：

| Minecraft版本 | Java版本       |
| ------------- | -------------- |
| 旧版本        | Java 7或Java 8 |
| 1.16          | Java 15        |
| 1.17          | Java 16        |
| 1.18          | Java 17        |

你可能会发现，旧版本的Java与新版本的外观、安装、使用都略有不同。这是Oracle JDK与Open JDK的区别，不要太在意。

因为我们不需要使用Java语言做开发，所以仅仅需要JRE（Java Runtime Environment）。但是实际可能会下载JDK（Java Development Kit），它会带有一份JRE。

以下仅介绍为较新版本Minecraft下载配置Java的过程.

1. 在官网（http://jdk.java.net/）找到合适的Java（JDK）版本。下图是下载Windows版本的例子。

   ![Java下载]({{< ref "/" >}}images/java/image-20220609235143084.png)

2. 下载完成后，无需安装，解压后便能使用。请将压缩包解压到你认为合适的地方。

3. 将 `Java/bin` 文件夹加入到 PATH 系统变量中。例如，你把JDK解压到了 `D:\Program Files\jdk-17.0.1`，其所包含的 `bin` 文件夹之地址为 `D:\Program Files\jdk-17.0.1\bin`。右键此电脑 – 高级系统设置 – 高级 – 环境变量，在下方“系统变量”中找到PATH（Path，不区分大小写）并双击，在弹出窗口中点击新建，填写 `D:\Program Files\jdk-17.0.1\bin`，点击确定关闭。

4. 测试：新建一个命令终端（cmd或者powershell），直接输入 `java.exe` 并回车。如果并未报“未找到命令”之错，表明配置成功。

