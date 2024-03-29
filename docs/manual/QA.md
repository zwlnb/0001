# 如何优雅的提问

> 编辑：PH
>
> **注意** ：Docs会不断地更新，请及时关注更新内容，以避免错误的操作引起的不必要的的后果

## 1.1 如何做提问前的准备?

**在你向社区或者其他非亲非故的同行咨询技术问题之前，你应该先做以下事情：**

1. 在社区的 issue 或者 FAQ 中尝试寻找答案 。
2. 尝试使用 google 搜索，不推荐使用 baidu ， 应使用关键词搜索，而不是口语化表述。如果使用的是国外的技术或框架，优先用英文关键词搜索。
3. 查看官方文档、使用手册。
4. 先自己思考或通过试验的方式尝试解决。即便解决不了，你也可以获得更多有用的信息。
5. 先找自己团队或者认识的发量较少的朋友咨询。
6. 如果你是程序员，尝试阅读源代码以找到答案。如果你不是或者你认为自己不是，请忽略此条。
7. 如果你做了上述事情，你就获得了向他人提问的资格。提问时，先说明你做了上述尝试，以及你从中发现了哪些关键信息，这会给对方留下一个好的印象。他们会觉得你是同道中人，也是一个努力上进的好青年。


## 1.2 如何提问？
### 1.2.1 仔细挑选提问的论坛
**在合适的地方提问，和提出一个好的问题同样重要，永远不要到肯德基里询问麦当劳怎么走。 Github issue 和 Stack Overflow 通常是很合适的编程问题的论坛，如果你不明白 Stack Overflow 的含义的话，那就不适合在那提问了，百度贴吧才是你真正的朋友。**

### 1.2.2 Github issue
**如果你用到 github 上的开源项目，那你可以先到 github 的项目官网中去搜索 issue ，看是否有类似的问题。如果没有的话，你可以提一个新的 issue 。 在提 issue 时，需要遵守官方对 issue 定义的格式和内容要求，否则你很难得到回复。国内的开源项目，你被回复的可能性是比较低的。 毕竟国内程序员的压力都比较大，开源生态环境也有待改进。这不是某一个作者或者组织的责任，开源兴亡，匹夫有责，提出一个好的问题，就是一个好的开端。**

### 1.2.3 官方组织的聊天群通常响应最快
**很多商业和开源项目都提供了聊天群，国外通常是 slack ,国内通常是 QQ 或 微信群 。在这些群里提问的话，通常会很快得到响应，而且群里都会有官方的技术支持人员解答问题。**

### 1.2.4 使用有意义且明确的标题
**在提问时，请使用简洁、清晰、一针见血的标题，自觉抵制那些无意义的口水话。『请问有没有人能帮帮我！！』 基本上与 在吗？同义。不要妄想用卑微、痛苦的语言去打动别人，技术社区不相信眼泪。**

>愚蠢：
</br>
救命啊！这个系统宕机了！ 你好 在吗！ 我用的主题报错了！ 我的网站不能登录后台怎么回事！
</br>
>明智：
</br>
java8 应用无响应，硬件资源正常
</br>
>更明智：
</br>
springboot 项目启动阻塞，启动线程卡在 dubbo 注册方法

### 1.2.5 用清晰、条理化、拼写正确的语句书写
**一个粗心与草率的提问者，通常也是一个粗心和草率的程序员，工作如此，生活亦如此。自己不认真对待遇到的问题，又岂能期望他人会认真对待。 用词正确简洁、条理清楚、详略得当，这样的问题更容易得到他人回复。 所有的技术社区都支持 markdown 语法（如果不支持，那它就不是一个技术社区），恰当的使用 markdown 语法，如高亮、加粗、列表等，能让你的问题更容易被他人理解。**

### 1.2.6 描述问题应准确且有内容
1.  仔细、清楚地描述问题的症状
2.  描述问题发生的环境（主机、操作系统、应用程序等）
3.  描述提问前做过的研究及其理解
4.  描述提问前为确定问题而采取的诊断步骤
5.  描述最近对计算机或软件配置的任何相关改变
6.  如果可能，提供在可控环境下重现问题的方法
7.  尽最大努力预测别人会提到的问题，并提前备好答案，这样可以提高沟通的效率。
8.  如果你认为是代码有问题，则应该提供可复现的测试代码和样例，这会让你得到回复的几率大幅增加。
9.  西蒙 · 泰瑟姆（_Simon Tatham_）写过一篇 如何有效报告Bug 的文章，我强烈推荐各位阅读。

### 1.2.7 别急于宣称找到Bug
**当你在一个软件或开源项目中遇到问题，除非你 非常、非常 的有把握，否则不要大声嚷嚷找到了Bug ， 轻则被打脸，重则被社区拉入黑名单。**
**提示：除非你直接定位到代码中的问题，或者出现和前面版本不一样的测试结果，否则你大概率是错的。**
**程序员听到别人声称找到 Bug 的第一反应是 “这不可能” ，第二反应是 “你用错了吧” 。 就算你真的找到 Bug 了，也应礼貌友好的指出。 大声嚷嚷：“你这写的啥呀，是不是没测试就发出来了呀” 对于解决问题没有帮助，只会得到“你行你上”的回复。**

### 1.2.8 有节制的提出请求
**直接要求他人帮你解决问题是愚蠢且自私的。在你遇到问题，寻求他人帮助时，你应抱着一定要自己解决的信念，别人只是给你提供解决思路和纠正错误。没有人有帮你解决问题的义务，合理有节制的提出请求，你才有可能得到他人的回复。**

### 1.2.9 礼多人不怪
**礼貌一点，使用『你好』、『请』、『谢谢』，让别人明白你感谢他们无偿的帮助。**

### 1.2.10 礼多人不怪
**有些人在他人帮助下解决了问题就销声匿迹，远走高飞。别人花费大量时间提供帮助，而他却在问题解决后不愿向帮助的人说明一下结果。问题解决后向所有帮助过的人回一条消息，让他们知道问题是如何解决的并再次感谢。有来有往，来日方长。如果问题比较复杂，可以梳理总结一篇文章发出来，一来可以自己巩固，二来可以帮助他人。前车之鉴，后事之师。**

## 1.3 如何理解别人的回复
### 1.3.1 RTFM和 STFW 意思是你的问题很傻很天真
**STFW , 全名是 Search The F--king Web ， 它还有个弟弟叫 RTFM, 全名是 Read The F--king manual 。 STFW 还有一个温和点的说法，叫 google is your friend ,对于不会科学上网的国内程序员，那就是 baidu is your friend 。如果你收到这样的回复，那这就是你能收到的最好的答案，你应该照做，去网上查一下，或者看一下手册。这样的回复虽然有些难以接受，但你不应该觉得被冒犯，因为别人已经给了你正确的答案。如果你还觉得难以接受，你应该把 STFW 设置为你的屏保，时刻提醒自己，别再提这么傻的问题了。**

### 1.3.2 对待无礼
**国内的评论区已基本被杠精占领，技术社区这一片唯一的净土也难以独善其身，肆意的谩骂、互相 diss 已是司空见惯。评论区的提示信息不是请遵守法律 ，就是善意的提醒善语结善缘，恶言伤人心。这是必须承受之痛，欲练此功。。欲带皇冠,必承其重。如果面对的是毫无意义的谩骂、轻视，这种纯粹的恶意仅仅是对方的一种发泄，目的就是引起你的愤怒。如果你愤怒了，那正中其下怀。如果对方只是无礼的给出了有用的信息，那就说明他是一个刀子嘴豆腐心的人，嘴上说着不要，但想要帮助别人的心还是很诚实的。如果你愤怒了，反倒显的小气了。**

## 1.4 别像失败者那样反应
**技术上的争论应该是君子之争，就事论事，理越辩越明。 谩骂、诋毁，或者是如祥林嫂般去知乎上宣称自己遭遇的不公正待遇，这样的回应只会让自己变成自己讨厌的那个人。君子量不极,胸吞百川流。不要做意气之争，不要把有限的精力放在无谓的争执上。 Big Endian or Small Endian , it's not a question .**

## 1.5 如何更好的回答他人
1.  态度和善一点。 遇到难题时的压力可能会让人显得无礼或愚蠢，但你要知道，这并不是真实的他。他只是遇到难处了，宽容善待他人，也是体现自己的良好修养。良言一句三冬暖，恶语伤人六月寒。
2.  对初犯者私下回复。 对那些无心之失没有必要当众羞辱。闻道有先后，术业有专攻，如是而已。人非生而知之者，大家都是从麻瓜做起的，一个真正的新手也许连怎么搜索或在哪找FAQ都不知道。回复别人 STFW 合理但不合情。
3.  没有十足把握，就别信誓旦旦 一个听起来权威的斩钉截铁的错误回复比没有回复还要糟，不要随意许诺，信誓旦旦地说“就是这的问题”。时刻记住，谦受益,满招损。
4.  可以不帮忙，但别瞎闹。 不要在具体步骤上开玩笑，有些可怜的麻瓜真的会把 rm -rf /* 当成重启指令。
5.  探索性的反问以启发提问者打开思路。 授人以鱼，不如授人以渔。探索性的反问、讨论比直接给出答案更难能可贵。
6.  从中发现自己软件的不足。当回复一个好问题时，问问自己 『如何修改程序或 FAQ 文档以免再次解答同样的问题？』。
7.  过程比结果更重要。如果你自己也是研究了很久之后才得到答案，那在回复他人时，不仅回复其然，最好是能回复其所以然。这个过程才是真正的价值所在。