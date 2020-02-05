# Project Undecided(定名后请修改)

SKY Comic Game Development Group(under construction)

Rev. 0.01

## ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 目标(随时可修改)

按照群内老哥们提出的几个基本背景设定，设计一款基于火焰之纹章的简洁**SRPG demo** 以吸引更多的志同道合的同伴加入到开发中来。 目前我们希望这款demo大致有两关，地图设计基本成型即可，敌方AI的设计取决于开发平台。

## ![#1589F0](https://placehold.it/15/1589F0/000000?text=+) 开发愿景

九层之台，起于累土。 游戏的开发非一朝一夕即可完成之事，考虑到各位志愿者时间也并不充裕，我们的开发周期以**两周**为一个段落。 版本控制程序是**github**(在代码不能使用的时候帮助我们回溯代码到上一个可用版本)，log文档请务必使用**markdown**语法完成。

## ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) 文件结构

待补全。

[上等人的提案](docs_demo/)

[个人进度记录](log/)

[图片](img/)

## ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) 备选制作工具

1. [SRPG Studio](https://store.steampowered.com/app/857320/SRPG_Studio/)

![Scheme](img/srpg_studio.jpg)

似乎是一款新晋游戏制作工具，可用于制作类似火纹一样的游戏，可自定义攻击帧，有少量素材附赠，不推荐steam购买因为我们尚且不知道是否会使用这个软件且对质量与后续支持一无所知。建议贴吧解决。

2. [RPG Maker](https://zh.wikipedia.org/wiki/RPG%E8%A3%BD%E4%BD%9C%E5%A4%A7%E5%B8%AB#RPG_Maker_MV)

![Scheme](img/rm.png)

RM不需要做过多介绍了，VX里面好像把之前的ruby换成了JavaScript。 用这个的毛病是这软件本身是拿来作RPG而不是SRPG的，因此要稍微动手写下JS插件，当然我认为网上一定有现成的可用，只是素质如何就不知道了。

3. [Pygame](https://www.pygame.org/news)

[平台上唯一一款SRPG，东方系列](https://www.pygame.org/project/1106)

![Scheme](img/pygame.png)

相对于前面两个，Pygame对用户的代码编写能力有更高的要求。Pygame是Python的一个包，包含一些搭建引擎的基本功能，使用这个包意味着我们还要自己开发引擎(弱鸡),周期会加长，灵活度会变大，难度也变大，但是因为并没有自带的素材，所以画面可能更加丑陋。


## ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) 基础教程：

不论是markdown还是github都只是工具，卡太久的话不用就完事了。

[Markdown](https://www.jianshu.com/p/q81RER) 亦或者直接使用任何文本编辑器打开这个README.md文件学习语法即可,我们用markdown只是为了统一log的格式而已。

[Github](tutorial/git.md)

[SRPG Studio](tutorial/srpg_studio.md)

SRPG Studio好像是你群呼声比较高的一个平台，奈何这平台并不支持中文，是故网上常见的教程都是英文，部分资源请参考上述链接。
