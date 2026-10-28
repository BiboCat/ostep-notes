# OSTEP 读书笔记

用我自己的话把 [*Operating Systems: Three Easy Pieces*](https://pages.cs.wisc.edu/~remzi/OSTEP/) 讲一遍。

不是译本，也不是知识总结，是读到哪儿、想到哪儿就记到哪儿；想不通的地方就原地留着。

## 目录

| 章 | 主题 | 笔记 |
| --- | --- | --- |
| 4 | 进程抽象 The Abstraction: The Process | [process.md](4-Processes/process.md) |
| 5 | 进程 API Interlude: Process API | [ProcessesAPI.md](5-ProcessesAPI/ProcessesAPI.md) |
| 6 | 受限直接执行 Mechanism: Limited Direct Execution | [Direct-Execution.md](6-Direct-Execution/Direct-Execution.md) 🚧 |

🚧 表示这篇还没写完，会在原文件上接着补，不另开新文件。

## 约定

- 术语第一次出现给英文，之后直接用：`inode`、`fd`、`trap`、`PCB`……
- 引用原文只引短句，并在下面标章节号；原文见上面第一个链接。
- 更新不定时，跟着读书进度走，不跟着日历走。

## 声明

个人学习笔记，非官方中文版，也不是译本。书中概念、图示与原文，版权归 Remzi H. Arpaci-Dusseau 和 Andrea C. Arpaci-Dusseau 所有。

本笔记文字采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 许可。
