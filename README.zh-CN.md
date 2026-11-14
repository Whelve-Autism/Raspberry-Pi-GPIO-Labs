<div align="center">

# 树莓派 GPIO 实验

**BCM 引脚编号 · LED 输出 · 答题反馈**

两份早期课程实验，记录如何用 Python 通过树莓派 GPIO 引脚驱动 LED。

[English](./README.md) · **简体中文**

</div>

[实验文件](#files)

<a id="files"></a>
## 实验文件

| 实验 | 内容 |
| --- | --- |
| [Lab #1](./Lab%20%231) | 点亮接在 BCM GPIO 18 的 LED，一秒后熄灭。 |
| [Lab #2](./lab%20%232) | 进行五道 Python 选择题，用 GPIO 17 和 18 上的绿灯和红灯反馈对错。 |

文件保留了原始实验命名，适合阅读参考。第一个使用 Python 2 的 `print` 语法。第二个需要整理缩进并导入 `RPi.GPIO`，才能作为独立脚本运行。
