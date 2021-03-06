---
title: 'Talk is cheap, show me your code  LeetCode入门有感'
date: 2017-10-16 00:29:41
tags: 编程有感
---

![Gilfoyle from *The Silicon Valley*](/images/Gilfoyle-from-The-Silicon-Valley.jpg)

理论上来说，在今年七月份初，我就应该算是正式投奔CS的怀抱了，然而因为各种乱七八糟的事，直到正式开学后，我才正式有了自己已经在学CS的感觉。
<!-- more -->
开学后，自然是花了点时间，了解了一下学校课程的要求水平，然后再给自己定个近期的主攻目标。考虑了一段时间后，就选择了算法作为首先攻破的第一个目标。回想起自己去年的时候，虽然已经把一些算法跟数据结构的大致思想都有所了解，但实际上，许多简单的算法题自己都还是做不来，现在回想起来，当时的自己不仅对它们的细节了解得不够，更重要的是，缺少了练习。毕竟纸上得来终觉浅，我等凡人，没有足够量的练习，显然是很难掌握一些新的知识的。自学的时候，最大的障碍，大概就是你几乎很难合理地去判断自己对知识的掌握程度，能完整地复述所学的概念的文字描述就算理解了吗？背下来就算理解了吗？显然都不是。在这种困境下，连“实践是检验真理的唯一标准”都帮不了你你想怎么实践？学个操作系统，上来就学写个操作系统吗？学编译原理，上来就写个编译器吗？这都不现实。就连你唯一最能实现的手段做习题，都很难检验自己掌握的程度。习题一般分为两种，除了简单的概念性的复述题目以外，还有一种是一些场景简化后，对某些知识点的运用，我个人是比较喜欢后一种类型的题目，但这种题目往往都难以找到题解。做没有题解的题目，就像把石头扔进深不见底的洞口一样，扔石头的人扔得越多，就越显得像个傻子。

常言道，理工类的书，看书不做题等于白看，做题没答案等于白做。大二虽然翻看了不少经典的书，但缺少应用实践，不仅看到的容易忘记，而且往往理解也不深刻，一旦涉及到的时候，明明这个东西自己看到过，也好像大概能懂，但实操起来却什么都做不了。

吸取之前的经验教训，现在再系统地学习算法跟数据结构，就再也不能光说不练了。想来想去，最靠谱的还是OJ（Online Judge），毕竟有足够多的Test Case来检验算法是否能通过边界条件，有时候大致的整体算法并不是很困难，但边界情况的考虑却很折磨人，培养考虑边界条件的缜密思维，对写代码还是很有好处的。虽然以前在POJ做过几题，但POJ的整体练习难度显然远远高于我目前的需求，最终还是选择了LeetCode，毕竟只要想工作，多少还是得刷一点LeetCode的算法题的嘛，拿工作的算法要求水平作为最低标准，还是很合理的；而且，LeetCode题解也比较丰富，试做几题后，基本一些经典题目下的discussion里都包含了典型的算法，简洁明了，除了部分题目收费跟Tag分类不太友好以外，还是不错的。

刚开始的一两天，我还是像之前做POJ上的题目一样，一道题死磕好久好久，几天下来都没做几题。心里估摸了一下，把LeetCode里600多题哪怕我只做一半，都大概得做到明年了吧！而且感觉题目没有大家说的那么简单啊！怕不是自己太蠢了？？说好的只是水题呢？？在一两天的自我否定当中，我想起了萧大在暑假开直播时说的话，大意就是：“有人说这个很难，想不到，想不到有什么关系呢，我现在告诉你，你学会了就是你的了”、“我布置的作业不是为了考倒你，而是为了让你学到知识”，我忽然意识到自己的问题所在：我是要学知识，根本没必要要求全部东西都独立地得出解法。倘若我自己就能独立地不停地得出一个又一个接近最优的算法模型，我就不会还留在这里上学了啊！从根本上来讲，我现在做的水题，跟听课时老师讲的例题是没有根本区别的。只不过形式上，课堂上的例题能有老师讲解，LeetCode上的水题的讲解就只有文字形式而已。课堂上，例题想不出来，老师是不会等全班每个人都独立想出来才公布答案的你都会了你还学什么啊。可见，在刷LeetCode的时候，正确的做法，应该是合理地控制独立思考的时间，死磕恰恰是最不经济的算法，尤其是在原本在这方面的知识储备较少的时候。看似勤奋独立的死磕，实际上更多地只是毫无头绪的思考与无厘头的尝试而已。在一道简单的题目前，如果在一定时间内仍然想不出来，正确的方法应该是看懂答案，弄懂答案的思路，构造出答案的前因后果，再独立地构建完整可运行的代码。随着题量的增多，再对题目与知识点进行归类、总结。

而在坚持一个星期下来后，写代码的感觉就已经完全不一样了。从简单的Array做起，然后是String、List、TwoPointers，再到今天的Tree，往日停留在纸上的算法思想，都在一题又一题切切实实的算法题目中得以体现。尽管现在还未能达到切Medium的水平，但至少面对Easy难度的时候再也不会一脸懵逼了。之前所看的《算导》里的内容、邓俊辉的《数据结构》里的奇技淫巧，都变得具体而深刻。

此时此刻，也终于切身体会到，所谓的“Talk is Cheap, Show Me Your Code"，是怎样一番体验了。从以前找题解的时候，不喜欢看代码都喜欢看文字解释，到如今对好的代码的接受程度变得远远高于文字表述，大概算是正式踏入写代码这样的大门吧？








