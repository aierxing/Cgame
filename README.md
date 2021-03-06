# Cgame
一些用C语言编写的小游戏, 大多数都是在控制台上实现基本功能  
代码极短, 可玩性高, 哪个初学者不想在黑漆漆的控制台玩游戏呢?  
仅支持windows下运行, 移植其他平台可作为参考代码  
代码均在Visual Studio 2017或gcc编译通过

使用说明:
1. `.c`文件, 不使用第三方库, 复制粘贴即可使用
2. 部分代码使用了c99特性, 比较远古的编译器&IDE可能需要`-std=c99`
3. 注意后缀是`.c`, 部分代码在`.cpp`会报错
4. 如果编译还是不通过可以加q群反馈

目前仅在bilibili发布有关视频  
bilibili ID: 你已经是大佬啦快和萌新们聊天吧 ([传送门](https://space.bilibili.com/345058248))  
如果想要交流的话, 欢迎加入作者的QQ交流群: 957964924
* * *
## 相关视频
目前仅在bilibili发布视频
|视频内容|文件夹名称|视频链接|
|-|-|-|
|五子棋|Five-in-a-row|[av969124292](https://www.bilibili.com/video/av969124292)|
|贪吃蛇|GluttonousSnake|[av85378627](https://www.bilibili.com/video/av85378627/)|
|俄罗斯方块|Tetris|[av85378627](https://www.bilibili.com/video/av85378627/)|
|扫雷|Minesweeper|[av87216317](https://www.bilibili.com/video/av87216317/)|
|2048|2048|[av89592082](https://www.bilibili.com/video/av89592082/)|
|窗口游戏|WindowGame|[av90604701](https://www.bilibili.com/video/av90604701/)|
|走迷宫|Maze|[av370410413](https://www.bilibili.com/video/av370410413)|
* * *
## 关于代码的相关声明
本存储库使用MIT开源协议  
代码主要用于交流学习使用,二次创作或商用都可以的,注明原作者就行,最好可以跟我说一下...  
* * *
## 目前所有的游戏
每个游戏有很多版本, 整理的比较乱, 就这样凑合着吧...
1. **俄罗斯方块(Tetris)**
    * chaos版本:11行,835个字符,gcc编译通过,实现基本功能
    * tiny版本:30行,减缓下坠速度&进一步压缩
    * tiny版本:33行,压缩&实现基本功能
    * annotation版本:在33行的基础上增加注释  
2. **贪吃蛇(GluttonousSnake)**
    * chaos版本:5行,358个字符,进一步压缩
    * tiny版本:14行,进一步压缩x2
    * standard版本:47行,展开&去闪烁
    * add版本:67行,增加了完善&拓展功能
    * screen版本:99行,用窗口组成贪吃蛇
3. **扫雷(Minesweeper)**
    * tiny版本:29行,压缩&实现基本功能
    * keyboard版本:25行,进一步压缩&优化交互
    * mouse版本:236行,完善了标志等功能，以及界面优化
    * Linux版本:31行,方便移植就顺便实现了
4. **2048**
    * tiny版本:22行, 进一步压缩
5. **窗口游戏(WindowGame)**
    * Snake:贪吃蛇
    * Tetris:俄罗斯方块
    * 2048:2048
6. **走迷宫(Maze)**
    * 26行，实现基本功能&去闪烁
7. **五子棋(Five-in-a-row)**
    * FIR:19行, 实现基本功能
    * AIv1:30行, 增加自动下子功能
    * AIv1(text):34行, 去闪烁&打印评估分
    * AIv1.1:34行, 优化界面
8. **敬请期待Coming soon...**
* * *
## 更新日志
|日期|内容|
|:-:|-|
|2020.9.13| 俄罗斯方块(tiny 24行)
|2020.9.4| 五子棋AIv1.1(界面优化)
|2020.8.10| 五子棋AIv1(30行)
|2020.7.24| 五子棋(19行)
|2020.7.17| 2048(22行)
|2020.7.4| 优化俄罗斯方块(tiny 30行)和扫雷(keyboard 25行)
|2020.7.4| 贪吃蛇(tiny 14行), 扫雷(Linux 31行)
|2020.6.26| 扫雷(keyboard 25行)
|2020.6.19| 贪吃蛇(chaos 5行)
|2020.6.13| 俄罗斯方块(tiny 30行)(chaos 11行)
|2020.6.13| 贪吃蛇(tiny 15行)(chaos 6行)(偷偷更新~)
|2020.4.30| 窗口游戏(源码)
|2020.4.24| 走迷宫(26行)
|2020.3.18| 把之前的代码全部生成.exe可执行程序，归纳在exe文件夹中
|2020.3.3| 窗口游戏(.exe)
|2020.2.21| 贪吃蛇(screen版本)
|2020.2.17| 2048(28行)
|2020.2.15| 扫雷(236行)
|2020.2.6| 扫雷(29行)
|2020.2.3| 创建了新的文件夹Older version归纳旧版本
|2020.1.29| 俄罗斯方块(2个版本),和一个旧版本38行
|2020.1.28| 贪吃蛇(3个版本)
|2019.12.27| 俄罗斯方块(48行)
|2019.12.15| 贪吃蛇(25行)
