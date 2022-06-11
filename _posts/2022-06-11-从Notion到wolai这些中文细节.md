# 从Notion到wolai，这些中文细节优化真是让人心动

```
---
layout: post
title: Notion and Wolai
---
```

[![奇客派](https://pic1.zhimg.com/v2-357c3a0c7ab62e429ec42ebf3fe7a23c_xs.jpg?source=172ae18b)](https://www.zhihu.com/people/shidongqi)

[奇客派](https://www.zhihu.com/people/shidongqi)

专注科技数码产品资讯及互联网行业分析。

90 人赞同了该文章

## **一、前言**

在年初一篇提及 Notion 的少数派文章中，我留下了这样一条评论，引起不少朋友的赞同和讨论：

![img](https://pic3.zhimg.com/80/v2-a9d4bd158dcb3d1ca17e6e3653804ee2_1440w.jpg)

没想到在这不久之后，我正式入了 Notion 的坑。Notion 真正吸引我的是 Database 以及无限的创造性。至此，我已经将大量的工作全部迁移到了 Notion 上，例如日常的文章整理、订阅服务、待办事项以及一些零零散散的笔记。

然而一段时间后，我有点后悔了，Notion 并没有兼容全部标准 markdown 格式，这让我在使用它长时间进行写作时非常煎熬，除了排版、格式、文件导出等都出现了一些麻烦，花了不少时间去研究如何改善工作流，但终究还是「将就」。

Notion 的创始人是华人，但我相信他一定不常用中文。服务器问题暂且不说，计划中的中文化进程迟迟没有结果，我也很难相信 Notion 会针对中文使用者进行特定优化。因此我也同样观望着另一款类似产品——wolai，从内测期使用至今，wolai 的中文编辑体验真的让我心动了。

## **二、wolai 近乎完美的中文编辑体验**

「国内版 Notion」，我和很多 Notion 用户一样都是对 wolai 有这样的初印象。wolai 的创始人马锐拉也坦然表示「从 Notion 身上得到了很多启发」。wolai 所做的并不只是完成汉化、服务器放在国内，对中文用户需求的深度把控或许才是核心竞争力。

### **1、中文排版优化**

对于文字工作者来说，内容排版其实是有一定习惯和讲究的。尤其是在中英文同时存在时，需要手动在中英文之间插入空格，接触到的不少网站排版都有这样的要求。

![动图封面](https://pic3.zhimg.com/v2-6ad39baccc211a875899c00cd34a784e_b.jpg)

在 wolai 中，有一定预设的样式，会自动在中英文内容插入间隔，无需手动输入空格以免影响输入流畅性。

![img](https://pic1.zhimg.com/80/v2-201a9f005b592d187b3532a01caee8b4_1440w.jpg)

也许局部例子无法看出差别，从大版面内容比较，不难发现中英文间隔之后，文字版面不会显得拥挤。当然，中英文加空格也并没有什么强制规定，更多的是个人使用习惯。

有一点需要说明，wolai 在中英文之间插入的间隔并非实际空格，只是样式上的限定。一旦将文字复制或者导出为本地文件，却是没有空格的。

![动图封面](https://pic1.zhimg.com/v2-6b5a44b12a81b60c85e1339235097a00_b.jpg)

![img](https://pic1.zhimg.com/80/v2-a11a801844389399330cf27093270484_1440w.jpg)

除此之外，在使用 Notion 时另一个让我比较难以接受的样式是「引用」格式。插入引用样式之后，字体大小明显变大，跟三级标题一般大小，太过于突兀，导致我只能尽量减少甚至不使用这个样式，这个问题我在使用 wordpress 编辑器中曾遇到过。

### **2、对 markdown 标准兼容更好**

### **2.1 markdown 引用格式的兼容**

作为 markdown 重度用户，以往都是使用纯粹的 markdown 写作工具，例如 Bear、iA Writer、Typora 等。而当我迁移到 Notion 上之后，发现其编辑器并没有支持全部的 markdown 标准格式，影响了原有的编辑效率。

![动图封面](https://pic3.zhimg.com/v2-73833d800f07318b3cad6b218d3768e6_b.jpg)

严格意义上来说，Notion 和 wolai 都不是标准的 markdown 编辑器，因为有更丰富的内容块形式，预设的一些快捷输入与 markdown 标准部分冲突。例如刚刚提到的引用样式，此前习惯的 markdown 标准是「>」+「空格」，而在 Notion 中会调出折叠列表样式，引用样式快捷输入是「"」+「空格」。

![动图封面](https://pic2.zhimg.com/v2-a58f1872fa6586c58ae77fc7be08433d_b.jpg)

wolai 编辑器几乎完整保留了常用的 markdown 标准格式，因此在使用习惯上基本不需要作调整，甚至还同时支持全角符号的快捷输入，这一点稍后会再提到。

![img](https://pic3.zhimg.com/80/v2-27d784e3276e49a7bb401e8a7cac8386_1440w.jpg)

此外，markdown 格式最多支持六级标题，Notion 中仅支持三级，wolai 中支持四级标题。

### **2.2 图片 markdown 格式支持**

单纯是输入格式上的差别其实并不多，倒不会产生多大影响，但对于 markdown 图片样式上的兼容，Notion 倒是给我带来了不少麻烦。

使用 markdown 进行本地写作的朋友，基本都会借助图床上传工具，直接获取 markdown 格式图片链接插入。但在 Notion 中无法直接插入 markdown 格式的图片地址，只能通过插入链接或者内容嵌入。

![img](https://pic2.zhimg.com/80/v2-08ecb92437aa40b0a67d6d094b6beee5_1440w.jpg)

![img](https://pic3.zhimg.com/80/v2-6f809b378fdf61bfadb046750147f68a_1440w.jpg)

手动插入方式需要通过快捷输入找到图片块，然后手动输入链接，等待图片加载；无法直接粘贴 markdown 图片格式，但可以通过粘贴图片 URL 地址，从弹窗中选择「嵌入图片」，等待图片加载即可。遗憾的是，这两种方式插入图片的加载时间都要至少等待几秒钟，体验并不好。

![img](https://pic4.zhimg.com/80/v2-28317a62c917eef85cda25dfe0cb8a5f_1440w.jpg)

但是，如果你的图床设置了图片处理，链接带有特定后缀，Notion 并不会识别为图片内容，但选择「内容嵌入」还是可以插入图片。

![img](https://pic1.zhimg.com/80/v2-09f5cf85003ef3e5b58d4d69120597d4_1440w.jpg)

这样插入的图片在导出 markdown 文件时会出现问题，带有图片处理后缀的图片导出会被识别为超链接内容，无法正确预览。

![动图封面](https://s2.loli.net/2022/06/08/VbogQxtLYuOwpSv.jpg)

上面提到的问题在 wolai 中都做了优化，直接粘贴 markdown 图片格式或者粘贴 markdown 全部图文，图片都会自动加载，在 Notion 中只能通过导入 markdown 文件。

![img](https://s2.loli.net/2022/06/08/qm3OlX9IfnbxteE.jpg)

当然 Notion 中两种图片插入方式在 wolai 中也是通用的，只是同样的问题是，如果直接粘贴带有图片处理后缀的 URL，wolai 中也无法识别为图片内容，且无法通过嵌入内容插入，但带有后缀的图片链接并不会影响导出 markdown 的格式问题。

### **3、快捷输入兼容全角符号及拼音，无需频繁切换输入法**

### **3.1 兼容中文输入状态下的全角符号**

wolai 的编辑体验最让我印象深刻的是对全角字符的兼容，这在其它编辑器中是非常少见的。无论是 Notion 的快捷输入还是 markdown 格式，一般都是需要在英文输入状态下支持，因此导致在中文输入中需要频繁切换输入法，但在 wolai 中则省事多了。

![动图封面](https://s2.loli.net/2022/06/08/8bFVK7IH9oiwmcU.jpg)

![img](https://s2.loli.net/2022/06/08/TG1w9xtVblcZWkf.jpg)

即便在中文输入法下，输入的全角字符效用等同于英文输入法下的符号，类似效果的有**引用样式、有序列表、待办事项、插入 Font Awesome 图标**等，这种输入体验对于中文用户非常友好。

### **3.2 快捷输入支持拼音及拼音首字母**

其次，在快捷输入中 wolai 也针对中文用户做了特殊优化。以图片块的快捷输入为例，如果沿用 Notion 的习惯，你需要输入「/image」或者「/picture」，这些都是英文输入习惯，对中文用户而言最友好的当然是拼音。

![img](https://s2.loli.net/2022/06/08/FVWKZlbXLjvgw2C.jpg)

在 wolai 中插入图片块，有多种调用方式，「/图片」「/tupian」、「/tp」、「/image」「/picture」等多种途径，同时兼容英文、中文拼音及拼音首字母。

![img](https://s2.loli.net/2022/06/08/p8qWiDrNz3JQAEK.jpg)

这些快捷输入方式在调用弹窗列表中都可以看到，默认展示最简短的首字母格式。当然也有少部分特殊的，比如插入网易云音乐，除了「/网易云音乐」、「/wyyyy」、「/music」等方式之外，「/163」也可以调用。而所有的这些调用方式往往不需要输入完整的字段就可以在列表中找到。

## **三、锦上添花的小功能**

除了中文输入体验的优化外，wolai 也给编辑器添加了一些增强使用体验的小功能。

![img](https://s2.loli.net/2022/06/08/w6hT4JuxQkPijO2.jpg)

![img](https://s2.loli.net/2022/06/08/TZCOlzQApP2o7JB.jpg)

wolai 默认添加了悬浮目录的样式支持，在页面菜单中可以开启，而不是 Notion 那样以内容块的形式插入。在宽屏下能够显示足够多的标题内容，支持点击快速跳转以及跟随页面滚动；在窄屏显示中，为了减少目录所占空间，则自动变成小黑条的状态，鼠标放上去即可预览标题。

![img](https://s2.loli.net/2022/06/08/iFWIgn2caAtLKMu.jpg)

当你鼠标放在标题内容上，你会看到文字上方会出现几个小圆点，一个小圆点表示当前为一级标题，四个小圆点则代表四级标题。

![img](https://s2.loli.net/2022/06/08/L9tGD2sylPInMTV.jpg)

类似的功能还有列表层级对齐线、空行提示、显示块结构、拼写检查等，均可以在菜单中开启。

## **四、丰富的多媒体内容深度贴合本土**

和 Notion 一样，wolai 中可以嵌入各种类型的多媒体内容，例如图标表情、音乐、视频等等。之前使用 Notion 时，发现其对国内大部分媒体服务都没有支持，以音视频为例，国外多用 Youtube、Spotify 等，国内这些基本不可正常使用。

![img](https://s2.loli.net/2022/06/08/mCUgdPWkJ3yVY9s.jpg)

既然 wolai 主要面向国内用户，这些内容势必以国内用户常用的为主，例如网易云音乐、B 站、腾讯视频等。

![img](https://s2.loli.net/2022/06/08/ZqTMhCbrmVYAxD3.jpg)

另外，如果你试图用 wolai 制定一个详细的旅游计划，利用「嵌入内容」的方式可以直接插入地图线路。

![img](https://s2.loli.net/2022/06/08/GzJghD3oNpZ1utE.jpg)

在添加题头图设置中，预设了部分图片，其中包括故宫博物院授权的国画风背景图。默认的图库除了 Unsplash 之外，还有 Pexels，都是知名免版权图库，实际体验中推测 wolai 针对这两个图库访问做了一定优化，在国内网络环境下加载图片比正常访问要更快。

![动图封面](https://s2.loli.net/2022/06/08/z2RNMLiHhQorJuG.jpg)

wolai 的页面图标内容比 Notion 丰富不少，除了 Emoji 之外，还可以添加 Font Awesome 图标，并且支持八种自定义颜色，并且在正文中也是可以自由插入使用的。当然，如果没有合适的，你也可以手动上传图标或者使用外链。

![img](https://s2.loli.net/2022/06/08/LTklHPSYWUe9g4y.jpg)

![img](https://s2.loli.net/2022/06/08/chdaIDkNupw3Clx.jpg)

默认支持动态日历作为图标，算是 wolai 的特色了，动态日历可以跟随实际日期变化自动变更，还能设定倒数日，一眼查看距离重要日子的时间。图片在外页中同样会显示在页面标题前面，效果其实还不错。除了这些，自定义图标还可以设置进度、特定的文字等，目测后期还会添加更多形式。

## **五、结语｜ wolai 不只是汉化的 Notion**

细节成为产品或服务质量的最有力的表现形式。wolai 不仅仅是汉化版的 Notion，用马锐拉的话说，wolai 融合了他所体验过的同类产品的所优点，包括 Notion、RoamResearch、wordpress 等。wolai 在对中文用户使用习惯的研究上，即便是 Notion 未来进驻国内市场也很难达到这样的程度。

除了中文界面之外，wolai 有着得天独厚的访问速度优势，再加之其编辑器对中文排版、输入以及 markdown 标准的几乎完美兼容，使其在细节体验上具有不俗的产品竞争力。

本文主要针对 wolai 对中文用户的优化进行了重点阐述，其实还有一些没提到的是 wolai 融入了多种形式的网络关系图、双向链接、快速创建今日速记以及独有的右侧边栏等功能，相信后续会有机会进行详细分享。

![img](https://s2.loli.net/2022/06/08/Su1EZnLACUIGWqX.jpg)

最后不得不提的是，我目前其实还是处于 wolai、Notion 同时使用的状态，主要原因是很多内容还是依赖 Notion 的 database 功能来进行管理。database 虽然早已出现在 wolai 的开发计划中，但上线时间未定，基于 wolai 对中文编辑体验的优化，或许 database 会更加值得期待。

发布于 2021-01-22 13:10

[Markdown](https://www.zhihu.com/topic/19590742)

[我来 wolai](https://www.zhihu.com/topic/21334312)

[Notion (软件)](https://www.zhihu.com/topic/20767752)

赞同 90

32 条评论

分享

喜欢收藏申请转载

### 文章被以下专栏收录

- [![奇客派](https://s2.loli.net/2022/06/08/Vl1XbipksEx5q23.jpg)](https://www.zhihu.com/column/qikepai)

- ## [奇客派](https://www.zhihu.com/column/qikepai)

- 安静地做最酷的极客。

### 推荐阅读

- # wolai云笔记事件的经过与思考

- 笔记软件是学习、工作、生活中不可或缺的重要工具，很有可能伴随着一生的使用，所以选择至关重要 从期望到失望这一切还得从 Notion说起，notion是国外一款异常强大的笔记软件，兼具美观实用…

- 钢铁板的意志

- ![笔记软件 FlowUs 综合评测](https://s2.loli.net/2022/06/08/GLilSsVhOU57AFp.jpg)

- # 笔记软件 FlowUs 综合评测

- 数字花园的...发表于效率软件综...

- ![我为什么不用Notion](https://s2.loli.net/2022/06/08/6ZYswy1QNOS2Joi.jpg)

- # 我为什么不用Notion

- 钱进笔记

- ![笔记软件选择对比：从 Wolai 到 FlowUs](https://s2.loli.net/2022/06/08/Iqh6Q7dD5NXKEnx.jpg)

- # 笔记软件选择对比：从 Wolai 到 FlowUs

- 数字花园的...发表于效率软件综...

## 32 条评论

切换为时间排序

写下你的评论...

发布

- [![张小凡](https://s2.loli.net/2022/06/08/pOwXSFZa6e1P3Dl.jpg)](https://www.zhihu.com/people/zhang-xiao-fan-89)[张小凡](https://www.zhihu.com/people/zhang-xiao-fan-89)2021-02-26
  
  像素级别。。。
  
  14回复踩 举报

- [![知乎用户](https://s2.loli.net/2022/06/08/8OcUT2wfWGtESLd.jpg)](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)[知乎用户](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)回复[张小凡](https://www.zhihu.com/people/zhang-xiao-fan-89)2021-03-16
  
  嘘，小心被封
  
  4回复踩 举报

- [![知乎用户](https://s2.loli.net/2022/06/08/XfayC7eQRvnDlb4.jpg)](https://www.zhihu.com/people/bccc59900c94e73f93ca5b5217c96606)[知乎用户](https://www.zhihu.com/people/bccc59900c94e73f93ca5b5217c96606)回复[知乎用户](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)2021-04-29
  
  哈哈哈哈哈哈哈
  
  1回复踩 举报

- [![一水米田](https://pica.zhimg.com/v2-03e64de5d05fe6bb014bc809b7549322_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/st1220)[一水米田](https://www.zhihu.com/people/st1220)2021-02-17
  
  Notion最大的优势是数据库支持呢
  
  4回复踩 举报

- [![Poulin](https://pica.zhimg.com/v2-abed1a8c04700ba7d72b45195223e0ff_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/a-bao-91-69-60)[Poulin](https://www.zhihu.com/people/a-bao-91-69-60)回复[一水米田](https://www.zhihu.com/people/st1220)2021-03-07
  
  语雀数据库也出了
  
  赞回复踩 举报

- [![YsJuliess](https://pic1.zhimg.com/v2-0946bf45c0e3f76d6fed540a6c668b24_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/ysjuliess)[YsJuliess](https://www.zhihu.com/people/ysjuliess)回复[一水米田](https://www.zhihu.com/people/st1220)2021-11-19
  
  wolai也出了
  
  赞回复踩 举报

- [![知乎用户](https://pic1.zhimg.com/da8e974dc_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/50295cb53326501a9f600f4fa1efb24b)[知乎用户](https://www.zhihu.com/people/50295cb53326501a9f600f4fa1efb24b)2021-04-05
  
  虽然Notion有时候要切换输入法使用快捷键有点麻烦，但是像素级ui和功能复刻真是让人不想用
  
  3回复踩 举报

- [![舆波](https://pic3.zhimg.com/v2-17cb768c010800f86fa7cb555814a27a_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/idavidma)[舆波](https://www.zhihu.com/people/idavidma)回复[知乎用户](https://www.zhihu.com/people/50295cb53326501a9f600f4fa1efb24b)2021-05-26
  
  我刚试了试我来，其实就是“、”也被设置成了开启快捷键的入口，而Notion只有“/”，但我相信Notion汉化之后也会有这个功能的。不过有个问题，就是这类笔记是否有随时导出全部笔记的功能，总是在云端很不放心啊。
  
  赞回复踩 举报

- [![LYC阿](https://pic1.zhimg.com/v2-6183b8b93570feaeda62eb68e29cae1c_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/duo-lun-duo-hao-yi)[LYC阿](https://www.zhihu.com/people/duo-lun-duo-hao-yi)2021-01-25
  
  notion国内链接太慢了 捏着鼻子转到wolai
  
  3回复踩 举报

- [![知乎用户](https://s2.loli.net/2022/06/08/8OcUT2wfWGtESLd.jpg)](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)[知乎用户](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)回复[LYC阿](https://www.zhihu.com/people/duo-lun-duo-hao-yi)2021-03-16
  
  现在已经好转了。好用
  
  2回复踩 举报

- [![陈不知](https://pic1.zhimg.com/v2-abed1a8c04700ba7d72b45195223e0ff_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/chen-bu-zhi-32)[陈不知](https://www.zhihu.com/people/chen-bu-zhi-32)2021-06-10
  
  wolai 3000个块就必须付费，这个有点。。。
  
  2回复踩 举报

- [![INKRUE](https://pic3.zhimg.com/v2-678c3269573f16e95dcb38684631f722_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/feihongink)[INKRUE](https://www.zhihu.com/people/feihongink)2021-03-26
  
  walai和Notion相似度极高。现在Notion国内访问的速度上来了![[思考]](https://pic4.zhimg.com/v2-bffb2bf11422c5ef7d8949788114c2ab.png)
  
  2回复踩 举报

- [![dejavudwh](https://pic1.zhimg.com/v2-91f979d6d769fd88a907e72b0ee7e526_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/shadow-61-66)[dejavudwh](https://www.zhihu.com/people/shadow-61-66)2021-02-24
  
  直接反手推荐一波思源和ob
  
  2回复踩 举报

- [![YsJuliess](https://pic2.zhimg.com/v2-0946bf45c0e3f76d6fed540a6c668b24_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/ysjuliess)[YsJuliess](https://www.zhihu.com/people/ysjuliess)回复[dejavudwh](https://www.zhihu.com/people/shadow-61-66)2021-11-19
  
  这俩和wolai 和notion感觉已经不在一个起跑线上了，现在的notion和wolai相互借鉴，越来越好用……我真的要笑死了
  
  2回复踩 举报

- [![知乎用户](https://pica.zhimg.com/da8e974dc_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/ef097fc9de1a263e6a88160223b3075b)[知乎用户](https://www.zhihu.com/people/ef097fc9de1a263e6a88160223b3075b)2021-04-26
  
  没有database，已卸载
  
  1回复踩 举报

- [![丶傻蠢憨](https://pic2.zhimg.com/v2-fc7b4924ae0e28fef7c3a4d51227cd30_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/zhu-sha-chun-han-75)[丶傻蠢憨](https://www.zhihu.com/people/zhu-sha-chun-han-75)03-10
  
  shachunhan诚挚邀请您注册并体验 wolai：
  我来 wolai - 不仅仅是未来的云端协作平台与个人笔记
  MXM57S3
  
  赞回复踩 举报

- [![知乎用户EN7esY](https://pic1.zhimg.com/v2-abed1a8c04700ba7d72b45195223e0ff_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/ting-jian-da-hai-de-sheng-yin-2018)[知乎用户EN7esY](https://www.zhihu.com/people/ting-jian-da-hai-de-sheng-yin-2018)2021-09-11
  
  wolai不能调节字体的大小，我把代码传上去特别小，看着眼睛疼
  
  赞回复踩 举报

- [![LUCKYPIN](https://pic1.zhimg.com/v2-8a05ca5e97b3873b3bc52d08b100196a_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/luckypin)[LUCKYPIN](https://www.zhihu.com/people/luckypin)2021-06-29
  
  请问markdown本地的照片可以随着markdown文件导入而上传上去吗
  
  赞回复踩 举报

- [![知乎用户](https://s2.loli.net/2022/06/08/8OcUT2wfWGtESLd.jpg)](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)[知乎用户](https://www.zhihu.com/people/d0435e705f33535cc5191990a74896c2)2021-03-16
  
  notion的速度上去了
  
  赞回复踩 举报

- [![知乎用户](https://pic1.zhimg.com/da8e974dc_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/aca95887d28cde50e4c64e7b2fcb5dae)[知乎用户](https://www.zhihu.com/people/aca95887d28cde50e4c64e7b2fcb5dae)2021-02-19
  
  请问，为什么datebase那么重要？
  
  赞回复踩 举报

- [![花开有时](https://pic1.zhimg.com/dddf19d2bb6b9a4be6c95681798eee3f_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/wang-yu-bin-52)[花开有时](https://www.zhihu.com/people/wang-yu-bin-52)回复[知乎用户](https://www.zhihu.com/people/aca95887d28cde50e4c64e7b2fcb5dae)2021-02-28
  
  可以用更多的方式组织处理数据
  
  2回复踩 举报

- [![丹丹](https://pic2.zhimg.com/v2-a8661adcc35497b2b6c66308a6c00684_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/dan-dan-43-71-94)[丹丹](https://www.zhihu.com/people/dan-dan-43-71-94)2021-02-12
  
  心动耶
  
  赞回复踩 举报

- [![知乎用户](https://pica.zhimg.com/da8e974dc_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/c84bbd59313891e1b41564e600849e73)[知乎用户](https://www.zhihu.com/people/c84bbd59313891e1b41564e600849e73)2021-02-11
  
  没liunx版本
  
  赞回复踩 举报

- [![TommyChanChan](https://pic2.zhimg.com/v2-7dafa05ed2a8443b60a568728bd74d1c_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/ai-zhi-shi-de-xiao-hang-hang)[TommyChanChan](https://www.zhihu.com/people/ai-zhi-shi-de-xiao-hang-hang)回复[知乎用户](https://www.zhihu.com/people/c84bbd59313891e1b41564e600849e73)2021-09-05
  
  有啊
  
  赞回复踩 举报

- [![知乎用户17G5a7](https://pic3.zhimg.com/v2-abed1a8c04700ba7d72b45195223e0ff_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/christopher.lee)[知乎用户17G5a7](https://www.zhihu.com/people/christopher.lee)2021-02-04
  
  全民人均一台vps走起
  
  赞回复踩 举报

- [![howie](https://pic2.zhimg.com/v2-47d5cbb39cb4a50ca6b3c6a3f750ec79_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/zhao-hao-39-36)[howie](https://www.zhihu.com/people/zhao-hao-39-36)2021-02-03
  
  notion在国内访问速度实在是太慢了
  
  赞回复踩 举报

- [![Carolyn](https://pic1.zhimg.com/0e7f691bd46d5bdf194b84d1597b0792_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/jiao-jiao-wu-96)[Carolyn](https://www.zhihu.com/people/jiao-jiao-wu-96)2021-02-02
  
  wolai手机可以用吗？
  
  赞回复踩 举报

- [![莓视界](https://pic3.zhimg.com/v2-9c2e89b61628c0659f2a0d6af1687cbd_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/mei-shi-jie-27-56)[莓视界](https://www.zhihu.com/people/mei-shi-jie-27-56)回复[Carolyn](https://www.zhihu.com/people/jiao-jiao-wu-96)2021-02-24
  
  好像目前没有移动版
  
  赞回复踩 举报

- [![知乎用户](https://s2.loli.net/2022/06/08/XfayC7eQRvnDlb4.jpg)](https://www.zhihu.com/people/4767924b1f1b8c6a70f9a5165e991c5e)[知乎用户](https://www.zhihu.com/people/4767924b1f1b8c6a70f9a5165e991c5e)回复[莓视界](https://www.zhihu.com/people/mei-shi-jie-27-56)2021-03-04
  
  官网说在三月上旬
  
  赞回复踩 举报

- 展开其他 1 条回复

- [![橙子璇](https://pic1.zhimg.com/v2-3b08c02a3f59325fc5e9e2cb96ef7c77_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/cheng-zi-xuan-21-30)[橙子璇](https://www.zhihu.com/people/cheng-zi-xuan-21-30)2021-02-01
  
  wolai在哪里下呀
  
  赞回复踩 举报

- [![康叔](https://pic1.zhimg.com/v2-7b27edb357b07c33f9c1c589c16d1cf7_s.jpg?source=06d4cd63)](https://www.zhihu.com/people/connor-martin)[康叔](https://www.zhihu.com/people/connor-martin)回复[橙子璇](https://www.zhihu.com/people/cheng-zi-xuan-21-30)2021-03-11
  
  这种百度可以找到答案的问题......就别伸手了