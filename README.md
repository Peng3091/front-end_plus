
👉 推荐 [在线阅读](http://programmercarl.com/) (Github在国内访问经常不稳定)         
👉 推荐 [Gitee同步](https://gitee.com/programmercarl/leetcode-master) 

> 1. **介绍** ：本项目是一套完整的刷题计划，旨在帮助大家少走弯路，循序渐进学算法，[关注作者](#关于作者)
> 2. **正式出版** ：[《代码随想录》](https://programmercarl.com/qita/publish.html) 。
> 3. **PDF版本** ：[「代码随想录」算法精讲 PDF 版本](https://programmercarl.com/qita/algo_pdf.html) 。
> 4. **算法公开课** ：[《代码随想录》算法视频公开课](https://www.bilibili.com/video/BV1fA4y1o715) 。
> 5. **最强八股文** ：[代码随想录知识星球精华PDF](https://www.programmercarl.com/other/kstar_baguwen.html) 。
> 6. **刷题顺序** ：README已经将刷题顺序排好了，按照顺序一道一道刷就可以。
> 7. **学习社区** ：一起学习打卡/面试技巧/如何选择offer/大厂内推/职场规则/简历修改/技术分享/程序人生。欢迎加入[「代码随想录」知识星球](https://programmercarl.com/other/kstar.html) 。
> 8. **提交代码** ：本项目统一使用C++语言进行讲解，但已经有Java、Python、Go、JavaScript等等多语言版本，感谢[这里的每一位贡献者](https://github.com/youngyangyang04/leetcode-master/graphs/contributors)，如果你也想贡献代码点亮你的头像，[点击这里](https://www.programmercarl.com/qita/join.html)了解提交代码的方式。
> 9. **转载须知** ：以下所有文章皆为我（[程序员Carl](https://github.com/youngyangyang04)）的原创。引用本项目文章请注明出处，发现恶意抄袭或搬运，会动用法律武器维护自己的权益。让我们一起维护一个良好的技术创作环境！


<p align="center">
<a href="https://programmercarl.com/xunlian/xunlianying.html" target="_blank">
	<img src="./pics/训练营.png" width="800"/>
</a>
</p>

# LeetCode 刷题攻略

## 刷题攻略的背景

很多刚开始刷题的同学都有一个困惑：面对leetcode上近两千道题目，从何刷起。

大家平时刷题感觉效率低，浪费的时间主要在三点：

* 找题
* 找到了不应该现阶段做的题
* 没有全套的优质题解可以参考

其实我之前在知乎上回答过这个问题，回答内容大概是按照如下类型来刷数组-> 链表-> 哈希表->字符串->栈与队列->树->回溯->贪心->动态规划->图论->高级数据结构，再从简单刷起，做了几个类型题目之后，再慢慢做中等题目、困难题目。

但我能设身处地的感受到：即使有这样一个整体规划，对于一位初学者甚至算法老手寻找合适自己的题目也是很困难，时间成本很高，而且题目还不一定就是经典题目。

对于刷题，我们都是想用最短的时间**按照循序渐进的难度顺序把经典题目都做一遍**，这样效率才是最高的！

所以我整理了leetcode刷题攻略：一个超级详细的刷题顺序，**每道题目都是我精心筛选，都是经典题目高频面试题**，大家只要按照这个顺序刷就可以了，**你没看错，README已经把题目顺序都排好了，文章顺序就是刷题顺序！挨个刷就可以，不用自己再去题海里选题了！**

而且每道题目我都写了的详细题解（图文并茂，难点配有视频），力扣上我的题解都是排在对应题目的首页，质量是有目共睹的。

**那么现在我把刷题顺序都整理出来，是为了帮助更多的学习算法的同学少走弯路！**

如果你在刷leetcode，强烈建议先按照本攻略刷题顺序来刷，刷完了你会发现对整个知识体系有一个质的飞跃，不用在题海茫然的寻找方向。

<div align="center"><strong>最新文章会首发在公众号「代码随想录」，扫码看看吧，你会发现相见恨晚！</strong></img></div>

<div align="center"><img src='./pics/公众号二维码.jpg' width=150 alt=''> </img></div> 

## 如何使用该刷题攻略

按照先面的排列顺序，从数组开始刷起就可以了，顺序都安排好了，按顺序刷就好。

在刷题攻略中，每个专题开始都有理论基础篇，并不像是教科书般的理论介绍，而是从实战中归纳需要的基础知识。每个专题结束都有总结篇，最这个专题的归纳总结。

如果你是算法老手，这篇攻略也是复习的最佳资料，如果把每个系列对应的总结篇，快速过一遍，整个算法知识体系以及各种解法就重现脑海了。

**这里每一篇题解，都是精品，值得仔细琢磨**。

我在题目讲解中统一使用C++，但你会发现下面几乎每篇题解都配有其他语言版本，Java、Python、Go、JavaScript等等，正是这些[热心小伙们](https://github.com/youngyangyang04/leetcode-master/graphs/contributors)贡献的代码，当然我也会严格把控代码质量。 

**所以也欢迎大家参与进来，完善题解的各个语言版本，拥抱开源，让更多小伙伴们受益**。

准备好了么，刷题攻略开始咯，go go go！

---------------------------------------------

## 前序

* [「代码随想录」学习社区](https://programmercarl.com/other/kstar.html)


* 编程语言
    * [C++面试&C++学习指南知识点整理](https://github.com/youngyangyang04/TechCPP)
    * [编程语言基础课](https://kamacoder.com/courseshop.php)
    * [23种设计模式](https://github.com/youngyangyang04/kama-DesignPattern)

* 工具 
    * [一站式vim配置](https://github.com/youngyangyang04/PowerVim)
    * [保姆级Git入门教程，万字详解](https://mp.weixin.qq.com/s/Q_O0ey4C9tryPZaZeJocbA)
    * [程序员应该用什么用具来写文档？](./problems/前序/程序员写文档工具.md)

* 求职 
    * [ACM模式练习网站，卡码网](https://kamacoder.com/)
    * [程序员的简历应该这么写！！（附简历模板）](./problems/前序/程序员简历.md)
    * [【专业技能】应该这样写！](https://programmercarl.com/other/jianlizhuanye.html)
    * [【项目经历】应该这样写！](https://programmercarl.com/other/jianlixiangmu.html)
    * [BAT级别技术面试流程和注意事项都在这里了](./problems/前序/BAT级别技术面试流程和注意事项都在这里了.md)
    
* 算法性能分析
    * [关于时间复杂度，你不知道的都在这里！](./problems/前序/时间复杂度.md)
    * [O(n)的算法居然超时了，此时的n究竟是多大？](./problems/前序/算法超时.md)
    * [通过一道面试题目，讲一讲递归算法的时间复杂度！](./problems/前序/递归算法的时间复杂度.md)
    * [关于空间复杂度，可能有几个疑问？](./problems/前序/空间复杂度.md)
    * [递归算法的时间与空间复杂度分析！](./problems/前序/递归算法的时间与空间复杂度分析.md)
    * [刷了这么多题，你了解自己代码的内存消耗么？](./problems/前序/内存消耗.md)


## 数组 

1. [数组过于简单，但你该了解这些！](./problems/数组理论基础.md) 
2. [数组：704.二分查找](./problems/0704.二分查找.md)
3. [数组：27.移除元素](./problems/0027.移除元素.md)
4. [数组：977.有序数组的平方](./problems/0977.有序数组的平方.md)    
5. [数组：209.长度最小的子数组](./problems/0209.长度最小的子数组.md)
6. [数组：59.螺旋矩阵II](./problems/0059.螺旋矩阵II.md)
7. [数组：总结篇](./problems/数组总结篇.md)

## 链表

1. [关于链表，你该了解这些！](./problems/链表理论基础.md)
2. [链表：203.移除链表元素](./problems/0203.移除链表元素.md)
3. [链表：707.设计链表](./problems/0707.设计链表.md)
4. [链表：206.翻转链表](./problems/0206.翻转链表.md) 
5. [链表：24.两两交换链表中的节点](./problems/0024.两两交换链表中的节点.md)
6. [链表：19.删除链表的倒数第 N 个结点](./problems/0019.删除链表的倒数第N个节点.md)
7. [链表：链表相交](./problems/面试题02.07.链表相交.md)
8. [链表：142.环形链表](./problems/0142.环形链表II.md)
9. [链表：总结篇！](./problems/链表总结篇.md)

## 哈希表

1. [关于哈希表，你该了解这些！](./problems/哈希表理论基础.md)
2. [哈希表：242.有效的字母异位词](./problems/0242.有效的字母异位词.md)
3. [哈希表：1002.查找常用字符](./problems/1002.查找常用字符.md)
4. [哈希表：349.两个数组的交集](./problems/0349.两个数组的交集.md)
5. [哈希表：202.快乐数](./problems/0202.快乐数.md)
6. [哈希表：1.两数之和](./problems/0001.两数之和.md)
7. [哈希表：454.四数相加II](./problems/0454.四数相加II.md)
8. [哈希表：383.赎金信](./problems/0383.赎金信.md)
9. [哈希表：15.三数之和](./problems/0015.三数之和.md)
10. [双指针法：18.四数之和](./problems/0018.四数之和.md)
11. [哈希表：总结篇！](./problems/哈希表总结.md)


## 字符串

1. [字符串：344.反转字符串](./problems/0344.反转字符串.md)
2. [字符串：541.反转字符串II](./problems/0541.反转字符串II.md)
3. [字符串：替换数字](./problems/kama54.替换数字.md)
4. [字符串：151.翻转字符串里的单词](./problems/0151.翻转字符串里的单词.md)
5. [字符串：右旋字符串](./problems/kama55.右旋字符串.md)
6. [帮你把KMP算法学个通透](./problems/0028.实现strStr.md)
8. [字符串：459.重复的子字符串](./problems/0459.重复的子字符串.md)
9. [字符串：总结篇！](./problems/字符串总结.md)

## 双指针法 

双指针法基本都是应用在数组，字符串与链表的题目上

1. [数组：27.移除元素](./problems/0027.移除元素.md)
2. [字符串：344.反转字符串](./problems/0344.反转字符串.md)
3. [字符串：替换数字](./problems/kama54.替换数字.md)
4. [字符串：151.翻转字符串里的单词](./problems/0151.翻转字符串里的单词.md)
5. [链表：206.翻转链表](./problems/0206.翻转链表.md)
6. [链表：19.删除链表的倒数第 N 个结点](./problems/0019.删除链表的倒数第N个节点.md)
7. [链表：链表相交](./problems/面试题02.07.链表相交.md)
8. [链表：142.环形链表](./problems/0142.环形链表II.md)
9. [双指针：15.三数之和](./problems/0015.三数之和.md)
10. [双指针：18.四数之和](./problems/0018.四数之和.md)
11. [双指针：总结篇！](./problems/双指针总结.md)

## 栈与队列

1. [栈与队列：理论基础](./problems/栈与队列理论基础.md)
2. [栈与队列：232.用栈实现队列](./problems/0232.用栈实现队列.md)
3. [栈与队列：225.用队列实现栈](./problems/0225.用队列实现栈.md)
4. [栈与队列：20.有效的括号](./problems/0020.有效的括号.md)
5. [栈与队列：1047.删除字符串中的所有相邻重复项](./problems/1047.删除字符串中的所有相邻重复项.md)
6. [栈与队列：150.逆波兰表达式求值](./problems/0150.逆波兰表达式求值.md)
7. [栈与队列：239.滑动窗口最大值](./problems/0239.滑动窗口最大值.md)
8. [栈与队列：347.前K个高频元素](./problems/0347.前K个高频元素.md)
9. [栈与队列：总结篇！](./problems/栈与队列总结.md)

## 二叉树 


题目分类大纲如下：           
<img src='https://code-thinking-1253855093.file.myqcloud.com/pics/20240424172231.png' width=600 alt='二叉树大纲'> </img></div>

1. [关于二叉树，你该了解这些！](./problems/二叉树理论基础.md)
2. [二叉树：二叉树的递归遍历](./problems/二叉树的递归遍历.md)
3. [二叉树：二叉树的迭代遍历](./problems/二叉树的迭代遍历.md)
4. [二叉树：二叉树的统一迭代法](./problems/二叉树的统一迭代法.md)
5. [二叉树：二叉树的层序遍历](./problems/0102.二叉树的层序遍历.md) 
6. [二叉树：226.翻转二叉树](./problems/0226.翻转二叉树.md) 
7. [本周小结！（二叉树）](./problems/周总结/20200927二叉树周末总结.md)
8. [二叉树：101.对称二叉树](./problems/0101.对称二叉树.md)
9. [二叉树：104.二叉树的最大深度](./problems/0104.二叉树的最大深度.md)
10. [二叉树：111.二叉树的最小深度](./problems/0111.二叉树的最小深度.md)
11. [二叉树：222.完全二叉树的节点个数](./problems/0222.完全二叉树的节点个数.md)
12. [二叉树：110.平衡二叉树](./problems/0110.平衡二叉树.md)
13. [二叉树：257.二叉树的所有路径](./problems/0257.二叉树的所有路径.md)
14. [本周总结！（二叉树）](./problems/周总结/20201003二叉树周末总结.md)
15. [二叉树：二叉树中递归带着回溯](./problems/二叉树中递归带着回溯.md)
16. [二叉树：404.左叶子之和](./problems/0404.左叶子之和.md)
17. [二叉树：513.找树左下角的值](./problems/0513.找树左下角的值.md)
18. [二叉树：112.路径总和](./problems/0112.路径总和.md)
19. [二叉树：106.构造二叉树](./problems/0106.从中序与后序遍历序列构造二叉树.md)
20. [二叉树：654.最大二叉树](./problems/0654.最大二叉树.md)
21. [本周小结！（二叉树）](./problems/周总结/20201010二叉树周末总结.md) 
22. [二叉树：617.合并两个二叉树](./problems/0617.合并二叉树.md)
23. [二叉树：700.二叉搜索树登场！](./problems/0700.二叉搜索树中的搜索.md)
24. [二叉树：98.验证二叉搜索树](./problems/0098.验证二叉搜索树.md)
25. [二叉树：530.搜索树的最小绝对差](./problems/0530.二叉搜索树的最小绝对差.md)
26. [二叉树：501.二叉搜索树中的众数](./problems/0501.二叉搜索树中的众数.md)
27. [二叉树：236.公共祖先问题](./problems/0236.二叉树的最近公共祖先.md)
28. [本周小结！（二叉树）](./problems/周总结/20201017二叉树周末总结.md)
29. [二叉树：235.搜索树的最近公共祖先](./problems/0235.二叉搜索树的最近公共祖先.md)
30. [二叉树：701.搜索树中的插入操作](./problems/0701.二叉搜索树中的插入操作.md)
31. [二叉树：450.搜索树中的删除操作](./problems/0450.删除二叉搜索树中的节点.md)
32. [二叉树：669.修剪二叉搜索树](./problems/0669.修剪二叉搜索树.md)
33. [二叉树：108.将有序数组转换为二叉搜索树](./problems/0108.将有序数组转换为二叉搜索树.md)
34. [二叉树：538.把二叉搜索树转换为累加树](./problems/0538.把二叉搜索树转换为累加树.md)
35. [二叉树：总结篇！（需要掌握的二叉树技能都在这里了）](./problems/二叉树总结篇.md)

## 回溯算法 

题目分类大纲如下：             

<img src='https://code-thinking-1253855093.file.myqcloud.com/pics/20240424172311.png' width=600 alt='回溯算法大纲'> </img></div>

1. [关于回溯算法，你该了解这些！](./problems/回溯算法理论基础.md)
2. [回溯算法：77.组合](./problems/0077.组合.md)
3. [回溯算法：77.组合优化](./problems/0077.组合优化.md)
4. [回溯算法：216.组合总和III](./problems/0216.组合总和III.md)
5. [回溯算法：17.电话号码的字母组合](./problems/0017.电话号码的字母组合.md)
6. [本周小结！（回溯算法系列一）](./problems/周总结/20201030回溯周末总结.md)
7. [回溯算法：39.组合总和](./problems/0039.组合总和.md)
8. [回溯算法：40.组合总和II](./problems/0040.组合总和II.md)
9. [回溯算法：131.分割回文串](./problems/0131.分割回文串.md)
10. [回溯算法：93.复原IP地址](./problems/0093.复原IP地址.md)
11. [回溯算法：78.子集](./problems/0078.子集.md)
12. [本周小结！（回溯算法系列二）](./problems/周总结/20201107回溯周末总结.md)
13. [回溯算法：90.子集II](./problems/0090.子集II.md)
14. [回溯算法：491.递增子序列](./problems/0491.递增子序列.md)
15. [回溯算法：46.全排列](./problems/0046.全排列.md)
16. [回溯算法：47.全排列II](./problems/0047.全排列II.md)
17. [本周小结！（回溯算法系列三）](./problems/周总结/20201112回溯周末总结.md)
18. [回溯算法去重问题的另一种写法](./problems/回溯算法去重问题的另一种写法.md)
19. [回溯算法：332.重新安排行程](./problems/0332.重新安排行程.md)
20. [回溯算法：51.N皇后](./problems/0051.N皇后.md)
21. [回溯算法：37.解数独](./problems/0037.解数独.md)
22. [回溯算法总结篇](./problems/回溯总结.md)

## 贪心算法 

题目分类大纲如下：             


<img src='https://code-thinking-1253855093.file.myqcloud.com/pics/20210917104315.png' width=600 alt='贪心算法大纲'> </img></div>

1. [关于贪心算法，你该了解这些！](./problems/贪心算法理论基础.md)
2. [贪心算法：455.分发饼干](./problems/0455.分发饼干.md)
3. [贪心算法：376.摆动序列](./problems/0376.摆动序列.md)
4. [贪心算法：53.最大子序和](./problems/0053.最大子序和.md)
5. [本周小结！（贪心算法系列一）](./problems/周总结/20201126贪心周末总结.md)
6. [贪心算法：122.买卖股票的最佳时机II](./problems/0122.买卖股票的最佳时机II.md)
7. [贪心算法：55.跳跃游戏](./problems/0055.跳跃游戏.md)
8. [贪心算法：45.跳跃游戏II](./problems/0045.跳跃游戏II.md)
9. [贪心算法：1005.K次取反后最大化的数组和](./problems/1005.K次取反后最大化的数组和.md)
10. [本周小结！（贪心算法系列二）](./problems/周总结/20201203贪心周末总结.md)
11. [贪心算法：134.加油站](./problems/0134.加油站.md)
12. [贪心算法：135.分发糖果](./problems/0135.分发糖果.md)
13. [贪心算法：860.柠檬水找零](./problems/0860.柠檬水找零.md)
14. [贪心算法：406.根据身高重建队列](./problems/0406.根据身高重建队列.md)
15. [本周小结！（贪心算法系列三）](./problems/周总结/20201217贪心周末总结.md)
16. [贪心算法：406.根据身高重建队列（续集）](./problems/根据身高重建队列（vector原理讲解）.md)
17. [贪心算法：452.用最少数量的箭引爆气球](./problems/0452.用最少数量的箭引爆气球.md)
18. [贪心算法：435.无重叠区间](./problems/0435.无重叠区间.md)
19. [贪心算法：763.划分字母区间](./problems/0763.划分字母区间.md)
20. [贪心算法：56.合并区间](./problems/0056.合并区间.md)
21. [本周小结！（贪心算法系列四）](./problems/周总结/20201224贪心周末总结.md)
22. [贪心算法：738.单调递增的数字](./problems/0738.单调递增的数字.md)
23. [贪心算法：968.监控二叉树](./problems/0968.监控二叉树.md)
24. [贪心算法：总结篇！（每逢总结必经典）](./problems/贪心算法总结篇.md)

## 动态规划

动态规划专题已经开始啦，来不及解释了，小伙伴们上车别掉队！

<img src='https://code-thinking.cdn.bcebos.com/pics/动态规划-总结大纲1.jpg' width=500> </img></div>
1. [关于动态规划，你该了解这些！](./problems/动态规划理论基础.md)
2. [动态规划：509.斐波那契数](./problems/0509.斐波那契数.md)
3. [动态规划：70.爬楼梯](./problems/0070.爬楼梯.md)
4. [动态规划：746.使用最小花费爬楼梯](./problems/0746.使用最小花费爬楼梯.md)
5. [本周小结！（动态规划系列一）](./problems/周总结/20210107动规周末总结.md)
6. [动态规划：62.不同路径](./problems/0062.不同路径.md)
7. [动态规划：63.不同路径II](./problems/0063.不同路径II.md)
8. [动态规划：343.整数拆分](./problems/0343.整数拆分.md)
9. [动态规划：96.不同的二叉搜索树](./problems/0096.不同的二叉搜索树.md)
10. [本周小结！（动态规划系列二）](./problems/周总结/20210114动规周末总结.md)

背包问题系列：

<img src='https://code-thinking.cdn.bcebos.com/pics/动态规划-背包问题总结.png' width=500 alt='背包问题大纲'> </img></div>


11. [动态规划：01背包理论基础](./problems/背包理论基础01背包-1.md)
12. [动态规划：01背包理论基础（滚动数组）](./problems/背包理论基础01背包-2.md)
13. [动态规划：416.分割等和子集](./problems/0416.分割等和子集.md)
14. [动态规划：1049.最后一块石头的重量II](./problems/1049.最后一块石头的重量II.md)
15. [本周小结！（动态规划系列三）](./problems/周总结/20210121动规周末总结.md)
16. [动态规划：494.目标和](./problems/0494.目标和.md)
17. [动态规划：474.一和零](./problems/0474.一和零.md) 
18. [动态规划：完全背包总结篇](./problems/背包问题理论基础完全背包.md)
19. [动态规划：518.零钱兑换II](./problems/0518.零钱兑换II.md)
20. [本周小结！（动态规划系列四）](./problems/周总结/20210128动规周末总结.md)
21. [动态规划：377.组合总和Ⅳ](./problems/0377.组合总和Ⅳ.md)
22. [动态规划：70.爬楼梯（完全背包版本）](./problems/0070.爬楼梯完全背包版本.md)
23. [动态规划：322.零钱兑换](./problems/0322.零钱兑换.md)
24. [动态规划：279.完全平方数](./problems/0279.完全平方数.md)
25. [本周小结！（动态规划系列五）](./problems/周总结/20210204动规周末总结.md)
26. [动态规划：139.单词拆分](./problems/0139.单词拆分.md)
27. [动态规划：多重背包理论基础](./problems/背包问题理论基础多重背包.md)
28. [背包问题总结篇](./problems/背包总结篇.md)

打家劫舍系列：

29. [动态规划：198.打家劫舍](./problems/0198.打家劫舍.md)
30. [动态规划：213.打家劫舍II](./problems/0213.打家劫舍II.md)
31. [动态规划：337.打家劫舍III](./problems/0337.打家劫舍III.md)

股票系列：

<img src='https://code-thinking.cdn.bcebos.com/pics/股票问题总结.jpg' width=500 alt='股票问题总结'> </img></div>


32. [动态规划：121.买卖股票的最佳时机](./problems/0121.买卖股票的最佳时机.md)
33. [动态规划：本周小结（系列六）](./problems/周总结/20210225动规周末总结.md)
34. [动态规划：122.买卖股票的最佳时机II](./problems/0122.买卖股票的最佳时机II（动态规划）.md)
35. [动态规划：123.买卖股票的最佳时机III](./problems/0123.买卖股票的最佳时机III.md)
36. [动态规划：188.买卖股票的最佳时机IV](./problems/0188.买卖股票的最佳时机IV.md)
37. [动态规划：309.最佳买卖股票时机含冷冻期](./problems/0309.最佳买卖股票时机含冷冻期.md)
38. [动态规划：本周小结（系列七）](./problems/周总结/20210304动规周末总结.md)
39. [动态规划：714.买卖股票的最佳时机含手续费](./problems/0714.买卖股票的最佳时机含手续费（动态规划）.md)
40. [动态规划：股票系列总结篇](./problems/动态规划-股票问题总结篇.md)

子序列系列： 

<img src='https://code-thinking.cdn.bcebos.com/pics/动态规划-子序列问题总结.jpg' width=500 alt=''> </img></div>


41. [动态规划：300.最长递增子序列](./problems/0300.最长上升子序列.md)
42. [动态规划：674.最长连续递增序列](./problems/0674.最长连续递增序列.md)
43. [动态规划：718.最长重复子数组](./problems/0718.最长重复子数组.md)
44. [动态规划：1143.最长公共子序列](./problems/1143.最长公共子序列.md)
45. [动态规划：1035.不相交的线](./problems/1035.不相交的线.md)
46. [动态规划：53.最大子序和](./problems/0053.最大子序和（动态规划）.md)
47. [动态规划：392.判断子序列](./problems/0392.判断子序列.md)
48. [动态规划：115.不同的子序列](./problems/0115.不同的子序列.md)
49. [动态规划：583.两个字符串的删除操作](./problems/0583.两个字符串的删除操作.md)
50. [动态规划：72.编辑距离](./problems/0072.编辑距离.md)
51. [编辑距离总结篇](./problems/为了绝杀编辑距离，卡尔做了三步铺垫.md)
52. [动态规划：647.回文子串](./problems/0647.回文子串.md)
53. [动态规划：516.最长回文子序列](./problems/0516.最长回文子序列.md)
54. [动态规划总结篇](./problems/动态规划总结篇.md)


## 单调栈 

1. [单调栈：739.每日温度](./problems/0739.每日温度.md)
2. [单调栈：496.下一个更大元素I](./problems/0496.下一个更大元素I.md)
3. [单调栈：503.下一个更大元素II](./problems/0503.下一个更大元素II.md)
4. [单调栈：42.接雨水](./problems/0042.接雨水.md)
5. [单调栈：84.柱状图中最大的矩形](./problems/0084.柱状图中最大的矩形.md)


## 图论 

通知：开始更新图论内容，图论部分还没有其他语言版本，欢迎录友们提交PR，成为contributor

1. [图论：理论基础](./problems/kamacoder/图论理论基础.md)
2. [图论：深度优先搜索理论基础](./problems/kamacoder/图论深搜理论基础.md)
3. [图论：所有可达路径](./problems/kamacoder/0098.所有可达路径.md)
4. [图论：广度优先搜索理论基础](./problems/kamacoder/图论广搜理论基础.md)
5. [图论：岛屿数量.深搜版](./problems/kamacoder/0099.岛屿的数量深搜.md)
6. [图论：岛屿数量.广搜版](./problems/kamacoder/0099.岛屿的数量广搜.md)
7. [图论：岛屿的最大面积](./problems/kamacoder/0100.岛屿的最大面积.md)
8. [图论：孤岛的总面积](./problems/kamacoder/0101.孤岛的总面积.md)
9. [图论：沉没孤岛](./problems/kamacoder/0102.沉没孤岛.md)
10. [图论：水流问题](./problems/kamacoder/0103.水流问题.md)
11. [图论：建造最大岛屿](./problems/kamacoder/0104.建造最大岛屿.md)
12. [图论：字符串接龙](./problems/kamacoder/0110.字符串接龙.md)
13. [图论：有向图的完全可达性](./problems/kamacoder/0105.有向图的完全可达性.md)
14. [图论：岛屿的周长](./problems/kamacoder/0106.岛屿的周长.md)
15. [图论：并查集理论基础](./problems/kamacoder/图论并查集理论基础.md)
16. [图论：寻找存在的路径](./problems/kamacoder/0107.寻找存在的路径.md)
17. [图论：冗余连接](./problems/kamacoder/0108.冗余连接.md)
18. [图论：冗余连接II](./problems/kamacoder/0109.冗余连接II.md)
19. [图论：最小生成树之prim](./problems/kamacoder/0053.寻宝-prim.md)
20. [图论：最小生成树之kruskal](./problems/kamacoder/0053.寻宝-Kruskal.md)
21. [图论：拓扑排序](./problems/kamacoder/0117.软件构建.md)
22. [图论：dijkstra（朴素版）](./problems/kamacoder/0047.参会dijkstra朴素.md)
23. [图论：dijkstra（堆优化版）](./problems/kamacoder/0047.参会dijkstra堆.md)
24. [图论：Bellman_ford 算法](./problems/kamacoder/0094.城市间货物运输I.md)
25. [图论：Bellman_ford 队列优化算法（又名SPFA）](./problems/kamacoder/0094.城市间货物运输I-SPFA.md)
26. [图论：Bellman_ford之判断负权回路](./problems/kamacoder/0095.城市间货物运输II.md)
27. [图论：Bellman_ford之单源有限最短路](./problems/kamacoder/0095.城市间货物运输II.md)
28. [图论：Floyd 算法](./problems/kamacoder/0097.小明逛公园.md)
29. [图论：A * 算法](./problems/kamacoder/0126.骑士的攻击astar.md)
30. [图论：最短路算法总结篇](./problems/kamacoder/最短路问题总结篇.md)
31. [图论：图论总结篇](./problems/kamacoder/图论总结篇.md)


（持续更新中....）


## 十大排序

## 数论 

## 高级数据结构经典题目 

* 并查集 
* 最小生成树 
* 线段树 
* 树状数组 
* 字典树 

## 海量数据处理

# 补充题目

以上题目是重中之重，大家至少要刷两遍以上才能彻底理解，如果熟练以上题目之后还在找其他题目练手，可以再刷以下题目：

这些题目很不错，但有的题目是和刷题攻略类似的，有的题解后面还会适当补充，所以我还没有将其纳入到刷题攻略。一些题解等日后我完善一下，再纳入到刷题攻略。


## 数组

* [1365.有多少小于当前数字的数字](./problems/1365.有多少小于当前数字的数字.md)
* [941.有效的山脉数组](./problems/0941.有效的山脉数组.md)  （双指针）
* [1207.独一无二的出现次数](./problems/1207.独一无二的出现次数.md) 数组在哈希法中的经典应用
* [283.移动零](./problems/0283.移动零.md) 【数组】【双指针】
* [189.旋转数组](./problems/0189.旋转数组.md)
* [724.寻找数组的中心索引](./problems/0724.寻找数组的中心索引.md)
* [34.在排序数组中查找元素的第一个和最后一个位置](./problems/0034.在排序数组中查找元素的第一个和最后一个位置.md) （二分法）
* [922.按奇偶排序数组II](./problems/0922.按奇偶排序数组II.md) 
* [35.搜索插入位置](./problems/0035.搜索插入位置.md)

## 链表

* [24.两两交换链表中的节点](./problems/0024.两两交换链表中的节点.md)
* [234.回文链表](./problems/0234.回文链表.md)
* [143.重排链表](./problems/0143.重排链表.md)【数组】【双向队列】【直接操作链表】
* [141.环形链表](./problems/0141.环形链表.md)
* [160.相交链表](./problems/面试题02.07.链表相交.md)

## 哈希表
* [205.同构字符串](./problems/0205.同构字符串.md):【哈希表的应用】

## 字符串
* [925.长按键入](./problems/0925.长按键入.md) 模拟匹配
* [0844.比较含退格的字符串](./problems/0844.比较含退格的字符串.md)【栈模拟】【空间更优的双指针】

## 二叉树
* [129.求根到叶子节点数字之和](./problems/0129.求根到叶子节点数字之和.md)
* [1382.将二叉搜索树变平衡](./problems/1382.将二叉搜索树变平衡.md) 构造平衡二叉搜索树
* [100.相同的树](./problems/0100.相同的树.md) 同101.对称二叉树 一个思路
* [116.填充每个节点的下一个右侧节点指针](./problems/0116.填充每个节点的下一个右侧节点指针.md)

## 回溯算法 

* [52.N皇后II](./problems/0052.N皇后II.md)
  

## 贪心
* [649.Dota2参议院](./problems/0649.Dota2参议院.md) 有难度
* [1221.分割平衡字符](./problems/1221.分割平衡字符串.md) 简单贪心

## 动态规划 
* [5.最长回文子串](./problems/0005.最长回文子串.md) 和[647.回文子串](https://mp.weixin.qq.com/s/2WetyP6IYQ6VotegepVpEw) 差不多是一样的
* [132.分割回文串II](./problems/0132.分割回文串II.md) 与647.回文子串和 5.最长回文子串 很像
* [673.最长递增子序列的个数](./problems/0673.最长递增子序列的个数.md) 

## 图论
* [463.岛屿的周长](./problems/0463.岛屿的周长.md) （模拟）
* [841.钥匙和房间](./problems/0841.钥匙和房间.md) 【有向图】dfs，bfs都可以
* [127.单词接龙](./problems/0127.单词接龙.md) 广搜

## 并查集 
* [684.冗余连接](./problems/0684.冗余连接.md) 【并查集基础题目】
* [685.冗余连接II](./problems/0685.冗余连接II.md)【并查集的应用】

## 模拟
* [657.机器人能否返回原点](./problems/0657.机器人能否返回原点.md) 
* [31.下一个排列](./problems/0031.下一个排列.md) 

## 位运算
* [1356.根据数字二进制下1的数目排序](./problems/1356.根据数字二进制下1的数目排序.md) 


# 算法模板 

[各类基础算法模板](https://github.com/youngyangyang04/leetcode/blob/master/problems/算法模板.md)

# 贡献者 

[点此这里](https://github.com/youngyangyang04/leetcode-master/graphs/contributors)查看LeetCode-Master的所有贡献者。感谢他们补充了LeetCode-Master的其他语言版本，让更多的读者受益于此项目。

# Star 趋势

[![Star History Chart](https://api.star-history.com/svg?repos=youngyangyang04/leetcode-master&type=Date)](https://star-history.com/#youngyangyang04/leetcode-master&Date)

# 关于作者

大家好，我是程序员Carl，哈工大师兄，《代码随想录》作者，先后在腾讯和百度从事后端技术底层技术研发。

# PDF下载 

添加如下企业微信，会自动发送给大家PDF版本，顺便可以选择是否加入刷题群。 

添加微信记得备注，如果是已工作，备注：姓名-城市-岗位。如果学生，备注：姓名-学校-年级。**备注没有自我介绍不通过哦**

<div align="center"><img src="https://code-thinking-1253855093.file.myqcloud.com/pics/第二企业刷题活码.png" data-img="1" width="200" height="200"></img></div>
