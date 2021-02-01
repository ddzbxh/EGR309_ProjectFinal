# EGR309_ProjectFinal_SC_NTMouse
DDL: June 2th, 2020

【说明】：

此项目是我已经完成的期末项目，实际使用了一些超纲的操作，但是代码本身还是有一定借鉴意义的，放出来供各位参考。

【目录】：

    各文件夹说明

    原项目要求

    我改动的操作

    一点吐槽

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

【程序】是程序本体

【效果】是实际实现的截图

【硬件】是我制作的硬件，没有原理图，以后可以考虑画个PCB版本

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

原项目要求：

1.工具：arduino开发板，伺服舵机（控制触控笔起落），手机（运行游戏“跳一跳”），尺子（测量屏幕）

2.目标：通过找到屏幕上的实际距离和按压时间的关系，写出一个能让舵机精确按压屏幕的程序，辅助跳一跳游戏

3.评分标准：跳一跳达到1000分为满分，直接折算成百分制

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

我改动的操作：

1.原项目只要求用面包板，这里我使用了万能板

2.原项目要求使用触控笔+手机+尺子（或把尺子替换成电脑投屏+像素测量），我改为了继电器+鼠标+电脑模拟器+像素测量

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

一点吐槽：

有一说一这个题属实NT。首先这个靠软件就能实现，Java它不香吗？Python它不香吗？另外，打分方式也是弱智，跳一跳实际在电脑上哪怕用像素测量，都还是会受到视角变化造成的干扰，1000分根本起不到检验效果。结合来看只不过是老师想不到好题了所以随便对付学生的，是这样吧！？

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

MIT License

Copyright (c) 2021 IlllIlIlIIlIl

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
