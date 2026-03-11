---
title: "SDVX-谱面制作与导入[Under Construction]"
description: 
date: 2026-03-11T11:51:45+08:00
image: 
math: 
license: 
comments: true
categories:
    - MUG
build:
    list: always
tags:
    - lost_archive
    - manual
---
发布于2023-05-19

正如其他音樂遊戲的譜面製作那樣，在製作前，你應當相對熟悉下官譜中的配置。
SDVX的譜面製作比其他音樂遊戲還要多兩步，
即對於fx的編輯和特效編輯
具體見bilibili [@-zade-](https://space.bilibili.com/3431129) 的教程 [こ ↑ こ ↓](https://www.bilibili.com/read/readlist/rl371766)

制作好后你可以通过ksm/usc进行简单的载入游玩，不再赘述 

下面的教程是关于导入HDD的

1.谱面转换

HDD运行的谱面格式是.vox，KSM/USC运行的谱面格式是.ksh，不过好在有现成的转换项目可供选择

[VoxCharger](https://github.com/SirusDoma/VoxCharger) (C#)

[ksh2vox](https://github.com/boringcactus/ksh2vox)(Python)

其中VoxCharger提供了GUI处理界面，易于上手，缺点是不支持音效和特效(截至20230519)，
ksh2vox则相反，不易上手但是支持音效特效的载入

2.音频转换