# My_Papers

这个项目记录了本人在读博士研究生期间发表的工作。

本人博士攻读期间研究方向为理论计算机，具体来说主要是图论，组合数学，最优化算法，布尔函数和量子计算。

下面是本人所发表和在投的部分工作。项目标题即为论文标题。所有论文均为理论性工作，本人均为第一作者或者共同第一作者，所有作者均按姓名拼音顺序排列。

## Structured Decomposition for Reversible Boolean Functions

问题背景：这篇文章是关于量子计算的一个子领域——可逆电路设计的讨论。量子元件的精度要求非常的高，因而对量子门来说，其所包含的量子比特数越少，其物理实现可行性就越高。因此如何利用低比特可逆布尔门的组合去实现多比特可逆布尔门就是一个很有意义的问题。

项目成果：本文证明了任一n比特可逆门可以由7个n-1比特可逆门复合得到，改进了前人9个的结果。为了可逆布尔电路能够递归地进行低维分解，我们同时给出了任一n比特偶置换可逆门可以由10个n-1比特偶置换可逆门复合得到，改进了前人13个的结果。我们同时利用代码实现了本文的结果，并被华为量子模拟平台HiQ收录。

发表期刊：IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems (TCAD'2020) (CCF体系结构A类, 中科院二区)

## On the Degree of Boolean Functions as Polynomials over Zm

问题背景：布尔函数是将0/1字符串映射为0/1的函数。布尔函数分析是计算复杂性理论和学习理论的核心问题之一，而一个通常的方法是将布尔函数用多项式进行表达，将其转化为纯代数问题。从代数的角度来说，一个多项式在不同域下的次数是值得关心的。

项目成果：利用线性代数和图论的方法，我们给出了关于布尔函数多项式表达取模后的次数下界的新的结果。具体来说，当m是素数或者素数幂，我们完全解决了这个问题；当m至少包含2个素因子且函数是对称布尔函数的时候，我们给出了一个渐进意义下紧的下界。

发表会议：International Colloquium on Automata, Languages, and Programming (ICALP'2020) (CCF理论B类)

## The One-Round Multi-player Discrete Voronoi Game on Grids and Trees

问题背景：一个图论博弈问题：若干个人玩一个游戏，在一张图上每人同时分别放一个棋子，图中每个点立刻归属于离其最近的那枚棋子（同时最近则该点无效）。每个人都希望自己的棋子控制的范围尽可能的大。

项目成果：本文主要研究了两类特殊的图——格点图和树。对于格点图，给出了玩家数小于等于4时存在纳什均衡的渐进充要条件；对于树，给出了玩家数小于等于3时判定是否存在纳什均衡的时空复杂度最优的算法。

发表期刊：Theoretical Computer Science (TCS'2020) (CCF理论B类，中科院四区)

## On the Relationship between Energy Complexity and other Boolean Function Measures

问题背景：能量复杂性是一个新兴的布尔函数测度，其与电路设计的能量消耗有密切关系。显然，我们希望对于布尔电路和布尔函数，其在物理实现上消耗的能量越小越好。

项目成果：本文的主要结果是证明了能量复杂性与判定树复杂性(一个被研究很广的布尔函数测度)有多项式上的大小关系，其中关于下界的结果是紧的，解决了前人关于能量复杂性的两个猜想。

发表会议：International Computing and Combinatorics Conference (COCOON'2019)

## Better Upper Bounds for Searching on a Line with Byzantine Robots

问题背景：分布式计算领域中，并行系统中拜占庭错误的处理是一个重要的问题。考虑如下模型：N个机器人在一条直线上进行协作搜索，共用一个通信网络，但是其中有K个对抗机器人，它们会尽可能干扰搜索过程的进行。要求设计通信协议和算法使得最坏情况下找到目标的时间尽可能短。

项目成果：我们设计了一个新的递归结构的算法，使得当5N/14<=K<N/2时，新算法相比原有算法效率有明显提升。

发表会议：Complexity and Approximation 2020
