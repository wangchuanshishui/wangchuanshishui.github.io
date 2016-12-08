---
layout: post
title: Source Insight使用技巧
categories: 效率
description: Source Insight使用技巧
keywords: 效率
---





# Source Insight使用技巧

我想任何一个C程序员都不可能不知道Source Insight，其优秀的品质，让我在开始工作的两天内立马抛弃大学时代用的Sublime，成为其忠实粉丝。因为实在是太方便了。唯一的缺陷就是无法折叠code。

### 添加SVN快捷键

添加SVN Diff快捷键

在source insight菜单Options->CustomCommands然后点击Add, Commandname设为svn DIff，run设为"C:\Program Files\TortoiseSVN\bin\TortoiseProc.exe" /**command:diff** /path:%f /notempfile/closeonend

**请注意要将TortoiseProc.exe的目录调整为自己电脑上的目录**。

其他快捷键

同上,command:diff改为以下命令

| command:commit              |        |
| --------------------------- | ------ |
| /command:update /path:%f /  |        |
| /command:update /path:*.* / | 更新整个目录 |
| command:lock                |        |
| command:revert              |        |
| command:log                 |        |

### 进阶使用

#### 宏

[官方宏](http://www.sourceinsight.com/public/macros/)

关于宏的时候用这篇[blog](http://www.cnblogs.com/wangqiguo/p/3713211.html)已经写的非常详细，我就不画蛇添足了。



配置分享:

这是我现在使用的[配置](https://github.com/wangchuanshishui/wangchuanshishui.github.io/blob/master/images/sourceInsight_config/GLOBAL.CF3)，应用前请备份自己的配置，因为每个人都有自己的喜好，如果你不喜欢还可以还原回去。











