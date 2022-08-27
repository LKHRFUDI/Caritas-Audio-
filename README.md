# Caritas-Audio

更新的版本的AI合成音频设计思路：

一、朗读内容：标题，正文，评论区补充内容，发布日期。
1.标题
2.正文（回答/文章）
3.评论区补充内容
——主要来自，已在主页发布了转载许可的答主。

二、朗读间隔、朗读节奏

在考虑要不要掐掉后面的日期：将文本发布日期纳入朗读范围，是想或许能方便听众留意版本更新的情况——但实际听下来——如果说一条知识性的音频可以在其播放之中以及完毕的短暂间隙里引人进入沉思，那么保留“播报日期和IP”这一设计，则可能更多地是在破坏引人沉吟的那片刻契机。

在开头部分的问题回答之间，中间部分的递进问答之间，留有1.2秒左右的空白时段——在尽可能缩短留白时间的前提下，1.2秒的留白或许是比起0.7秒、0.9秒的留白更不容易让人觉得突兀的时间间隔。

由同一部分内容制作的合成音频可能不断更新的原因，主要在于，

南山 制作的版本也给了我很多启发：
比如我只凭着自己的能力、长久地未发现的「乡愿」那一篇里——“看（kān）场子”中，“看”字的读法。



# Caritas-PDF

可在GitHub网页端浏览，与Caritas-Word的区别仅仅在于文件类型。

# Caritas-Word

为了使需要再次阅读的文本从排版上看更具可读性，在阅读过程中对Caritas系列阅读文本做了一定程度的粗排版。

关于阅读稿的排版设计思路：

一、为使单次浏览扫入尽可能多的信息、方便训练速读：

1）将字号设置为（尽可能小的）10号字——每行至多大约有45个字符；

2）将段落中，段前间距设置为1.15磅，段后间距设置为4.65磅，行距值设置为固定值12磅，制表位设置为2字符——姑且将这些参数称为“1.15-4.65-12-2”——然后将“1.15-4.65-12-2”设置为默认值，并应用于“所有基于Normal模板的文档”——这组设置主要体现在评论区的排版上：

<img width="312" alt="image" src="https://user-images.githubusercontent.com/52726689/187008921-ac449f0e-0958-48ef-856b-e5e574fbeb12.png">

在“1.15-4.65-12-2”的段落间距中「“换行”符所分隔出的上下两行间距」大于「“制表符”的上下两行间距」

不同组评论：以“换行”符分隔每组评论；

同一组（参与讨论人数大于1的）评论：以“制表符”分隔每个评论；

同时，在回答区或文章的正文部分，以制表符（Tab）或段落设置内的“首行缩进2字符”控制首行缩进。

<img width="83" alt="image" src="https://user-images.githubusercontent.com/52726689/187009458-918aa6b5-8aae-4cc5-8902-72564b04f9a6.png">

在我的操作系统（环境）中，将“1.15-4.65-12-2”设置为默认值，并应用于“所有基于Normal模板的文档”后，新建文档时仍然存在的一些误差：
A.无伤大雅的误差：
a.尽管将制表位设置为2字符，但在新创建的文档里——往往默认制表位显示为“2.1字符”；
b.尽管未更动缩进值、或在发现缩进值不为0时将缩进值更动制表位设置为2字符，但在新创建的文档里——往往默认制表位显示为“2.1字符”；
<img width="312" alt="image" src="https://user-images.githubusercontent.com/52726689/187009976-4ed4d9af-e3a2-44fb-ab22-12239e8b5e6b.png">


B.需要修正的误差：尽管将段后间距设置为4.65磅，但在新创建的文档里——往往默段后间距显示为“8.15 磅”；
<img width="311" alt="image" src="https://user-images.githubusercontent.com/52726689/187009953-0e9680f4-55ff-42ec-981e-ba70c73baef1.png">



二、为方便阅读时，在PDF文稿或A4纸张打印的阅读稿件上作批注：
（基于第一条思路，给阅读过程尽可能留出一些思考空间）
1）将文稿布局中的页边距设置为大约2.5cm的左右页边距；



个人经验：将阅读稿用A4纸打印阅读，或用A4大小的e-ink设备阅读文稿——有助于总览文章结构，也可以作为一种缓解视疲劳的有效手段。
