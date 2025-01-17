# 一个Python助教的学期总结

俗话说的好，你要是觉得xx不好，你就去建设它。上个学期我曾在98发过[一个帖子](https://www.cc98.org/topic/5215387)，简单概括了我对本科教学的一些看法，也引起了一些讨论。我在里面曾提到本科教学的一大弊病是助教不足，所以这个学期我报名去担任了《Python程序设计》这门计算机通识课程的两个班的助教，来简单说一下我在担任助教过程的一些所见所闻。

首先说明一下，《Python程序设计》并不是专业课，而是一门面向非计算机专业的通识课程，因此我所在的班级基本什么专业的同学都有，当然也有一些计院的同学来刷分的。这门课程讲的东西实际上非常少，主要就是最基本的一些python语法和简单的python程序编写，我觉得这门课主要的难点在于应付期末理论考试而不是做出编程题。我在担任助教的这段时间里也主要负责为同学解答编程题方面的问题。这个过程中，我发现，事情没有我所想的这么简单。

先分享几个担任助教过程中遇到的有趣的事情，每个故事我都起了一个小标题：

## 开门大吉

刚开学的时候，需要安装Python以及相关的开发环境Thonny，一个月过去之后仍然有非常多的人不会用Thonny，包括很多基本的操作比如如何创建文件，如何运行写好的代码。很多人喜欢把题目里的代码直接复制到Thonny的shell里面运行，但由于空格的问题，这么搞往往是运行不了的。我多次强调之后依然有人这么搞并且来问我。

## 持之以恒

我曾写了一个语雀文档来总结每周编程题出现的一些易错点，并在里面写了**如何用print法debug**，**如何设计测试用例来检查代码的正确性**，这些内容我也在班级群里多次强调，并要求同学在提问编程题之前，先把自己设计的测试用例和运行结果等东西发我看看。

遗憾的是，来找我的同学里面依然有非常多的人不会自己debug(哪怕是print一下中间结果呢)，也没有设计过测试数据看看边界情况对不对，往往是在自己没有任何思路说明的情况下直接在钉钉上甩我一串代码让我看。

## 与人为善

### 十万火急

有的同学答疑喜欢用命令式的语气来提问，比如曾有人跟我说“啥时候有想法可以跟我讲讲”，也有的同学在忘记做作业的时候，会在星期天晚上十点给我连打四五个钉钉电话要我重新开发题目集，并且发给我的每条消息都要钉一下让我确认查收。当我说这你得询问老师意见的时候，这位同学又紧接着给老师打了五个钉钉电话。

### 逻辑闭环

另一个同学在上机课的时候跟我说，上周PTA一直登不上去，今天才登上，能不能重新开放一下题目集让我补交作业。

我觉得很奇怪，别人都登录了怎么你登不上。用教师的账号去看了一下，这个同学上周上机课就已经登录并打开了题目集，并问TA为什么。

这位同学说，我是用ipad登的。我说，你ipad能登，为什么电脑登不上。你真急着做题，怎么不先用ipad把理论题做了。

然后TA说，我以为是机房电脑有问题。我说当时我就在机房，你咋不跑来跟我说，今天才来。

这位同学的钉钉已读不回。后续老师还是开放了题目集，允许作业补交。你没做作业就是没做作业，何必整一套说辞来坑蒙拐骗呢？

## 上下求索

**有非常多的人，平时作业的代码是直接抄袭CSDN的**，虽然这门课不查重，但这并不代表助教不知道有人在抄代码。具体的表现有：

### 贼喊捉贼

有人在考试或者小测之前，**拿着自己之前提交的代码来问我为什么要这么写**，我说这不是你自己写的吗你怎么还不知道了。然后**我发现使用百度搜索引擎搜出的第一条来自CSDN的解答代码和这位同学提交的代码完全一致**。所以我拒绝了这位同学的提问。

### 延迟满足

另一个同学也是在小测之前，发给我一道前几周的题，说自己不会做了，我说这不是前几周的作业吗，怎么现在才发现不会做，然后我去看了一下，这位同学天赋异禀，经常在每周上课前就做完了本周编程题，**曾有一次在题目集刚开放的时候，仅用时不到十分钟就做完了本周所有编程题，并且都是一次性通过**。我跟这位同学说明情况之后，TA对我说：那总不能空着不做吧？

### 人设崩塌

我们班每次小测的编程题都是**从前几周的作业里面来**的，但是每次小测编程题能获得满分的人往往**不超过一半**，甚至有很多人平时作业次次满分，一到小测就0分的。

我在多次监考的过程中注意到，有一位同学考试的时候好像经常忙着跟人微信聊天，不过TA前几次小测成绩都挺好的。在期中考试的时候，我搬了条凳子坐到这位同学附近去监考。可能是附近坐了个人有点紧张，这位同学期中考发挥失利，理论题就对了一半，编程题更是一道题都没做。对此我深表遗憾。

------------------------------------------------------------------------------------------------------------------------

像这样的故事在我当助教的这段时间里还有很多，实际上这门课16周就学了最基本的python语法(我印象里就学了列表，字典，for循环，if-else语句和函数，差不多就只有C小程一半的内容)，老师讲的应该还是比较慢的，我觉得但凡花点心思，也不至于出现上述种种情况。

班上很多同学在完全没学会的情况下，依然选择抄代码敷衍了事。我曾多次在班级群和自己写的语雀文档里提到过，如何进行debug，如何自己编测试数据，以及不要去网上搜答案抄作业，而事实就是，没有几个人真的做到了。但是学习编程，学会自己发现代码中的bug，自己编测试点去测代码里的bug，比学会语法(事实上我敢说一个学期过去了，很多人连这个都没学会)、会做理论题会考高分重要的多。

另外，Python这门课可能也有各种各样的问题，我觉得它的总体质量并不高，大部分时候还是填鸭式的教学，跟高中信息技术课无异，不过这又是后话了。之前的帖子我尝试从学生的视角来反映教学过程中存在的各种问题，而这一次，我站在一个助教的角度，记录了实际教学过程中，学生层面同样存在的各种问题。这些事情乍一看令人开怀，可仔细一想，却让我感到非常郁闷，因为就算是这样的基础课，它在教学的各个环节中也依然存在各种各样的问题。