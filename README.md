# NOTES

> **🏳️ 求生欲**
>
> 此仓库，仅作为个人学习时的「笔记」；  
> 所有的写作和整理工作，于「家中」并「空闲时间」独自完成，未曾产生收益，也不谋求收益；  
> 其中的内容，与个人「从前」「现在」以及「未来」所从事的工作「无关」；
>
> *如果涉及到任何版权等法律行为，请联系我，我将删除内容。*

<p>
    <a>
        <img src="https://img.shields.io/badge/mardown-writing-white?logo=markdown" />
    </a>
    <a>
        <img src="https://img.shields.io/github/license/doongz/notes?color=white" />
    </a>
    <a>
        <img src="https://img.shields.io/github/repo-size/doongz/notes?color=white&logo=git&logoColor=white" />
    </a>
    <a>
        <img src="https://img.shields.io/github/stars/doongz/notes?color=white&logo=github" />
    </a>
    <a>
        <img src="https://img.shields.io/github/last-commit/doongz/notes?color=white&logo=github" />
    </a>
    <a>
        <img src="https://img.shields.io/github/commit-activity/m/doongz/notes?color=white&logo=github" />
    </a>
</p>
## *Contents*

### *Chapter-1 [Problem Solving](./Algorithm)*

> 主要是一些模版和~~套路~~，方便在 codeforces 和 leetcode 的比赛时~~快速上分~~

- [前述](./Algorithm/0-前述/)  `C++调试模版`  `常见报错`  `自定义排序合集`
- **数据结构**  [🧾例题清单](./Algorithm/1-数据结构/)
  - [基本概念](./Algorithm/1-数据结构/0-基本概念.md)  `基本概念`  `算法评价`
  - [线性表](./Algorithm/1-数据结构/1-线性表.md)  `顺序存储(数组)`  `环状数组`  `链式存储(链表)`  `哨兵`  `多画`  `舍得变量`  `双指针`  `环状链表`  `Medium`
  - [栈](./Algorithm/1-数据结构/2-栈.md)  `顺序、链式存储`  `单调栈`  `表达式求值`  `递归`  `移除问题`   `Medium`
  - [队列](./Algorithm/1-数据结构/3-队列.md)  `顺序、链式、双端`  `单调队列`  `层遍历`  `Medium`
  - [字符串](./Algorithm/1-数据结构/4-字符串.md)  `顺序、堆分配、块链存储`  `KMP算法(子串包含问题)`
  - 树
    - [树 & 二叉树](./Algorithm/1-数据结构/5-1-树和二叉树.md)  `树的种类`  `二叉树遍历(前序、中序、后序、层)`  `二叉树构造「未完工」`   `线索二叉树`  `Easy`
    - [树的拓展](./Algorithm/1-数据结构/5-2-树的拓展.md)  `平衡树`  `二叉搜索树BST`  `平衡二叉搜索树AVL`  `红黑树`  `查找、插入、删除 O(logn)`
    - [并查集](./Algorithm/1-数据结构/5-3-并查集.md)  `连通`  `连通分量`  `连通性判断`  `添加、连通、查找O(logn)`  `Medium`
    - [树状数组 ](./Algorithm/1-数据结构/5-4-树状数组.md)  `维护区间信息`  `单点更新O(logn)`  `区间查询O(logn)`  `Hard+`
    - [线段树](./Algorithm/1-数据结构/5-5-线段数.md)
    - [字典树](./Algorithm/1-数据结构/5-6-字典树.md)  `前缀树`  `字符串/字符前缀是否存在`  `节点存什么值`  `遍历字典树`  `Hard`
    - [哈夫曼树](./Algorithm/1-数据结构/5-7-哈夫曼树.md)
    - [B树 & B+树](./Algorithm/1-数据结构/5-8-B树&B+树.md)
    - [红黑树](./Algorithm/1-数据结构/5-9-红黑树.md)
  - [散列表](./Algorithm/1-数据结构/6-散列表.md)  `哈希表`  `本质-数组`  `核心-散列函数`  `哈希冲突`  `扩容`  `查找`  `原地哈希`
  - [堆](./Algorithm/1-数据结构/7-堆.md)  `优先队列`  `大/小根堆`  `TopK`  `多路归并`  `中位数`  `插入O(logn)`  `查找O(1)`  `删除O(logn)`  `Hard`
- **算法基础**  [🧾例题清单](./Algorithm/2-算法基础/)
  - [排序](./Algorithm/2-算法基础/01-排序.md)  `选择O(n^2)`  `冒泡O(n^2)`  `插入O(n^2)`  `计数O(n)`  `桶O(n)`  `快速O(nlogn)「未完工」`  `归并O(nlogn)`  `外部排序「未完工」`  `Hard`
  - [二分法](./Algorithm/2-算法基础/02-二分法.md)  `不可套模版`  `二段性`  `寻找一个数`  `lower_bound`  `upper_bound`  `O(logn)`  `三分`  `Hard+`
  - [专题 二分答案](./Algorithm/2-算法基础/02-专题-二分答案.md)
  - [双指针](./Algorithm/2-算法基础/03-双指针.md)  `快慢双指针`  `左右双指针`  `前后双指针`  `指向各自集合的双指针`  `Floyd判圈算法`  `时O(n)`  `空O(1)`  `Medium`
  - [滑动窗口](./Algorithm/2-算法基础/04-滑动窗口.md)  `单调性`  `窗口数据结构`  `右边届入窗`  `左边届收缩`  `延时删除`  `采集答案`  `步长`  `起始位置`  `Medium`
  - [前缀和](./Algorithm/2-算法基础/05-前缀和.md)  `相减`  `哈希表`  `二维前缀和`  `前缀和思想`
  - [差分](./Algorithm/2-算法基础/06-差分.md)  `两端操作`  `操作区间从O(k)降至O(1)`  `二维差分`
  - [贪心](./Algorithm/2-算法基础/07-贪心.md)  `排序预处理`  `区间调度问题`  `跳跃问题`  `环形贪心`  `堆`  `单调栈`  `Hard`
  - [位运算](./Algorithm/2-算法基础/08-位运算.md)  `>>i逐位考察`  `异或`  `奇偶`  `除2`  `乘2`  `2的n次方`  `求中值`  `平均数`  `交换值`  `加法`  `1个数`  `滚动数组`  `状态压缩`
  - [分治](./Algorithm/2-算法基础/09-分治.md)  `分解 -> 解决 -> 合并`
  - [模拟](./Algorithm/2-算法基础/例题-模拟)
- **动态规划**  [🧾例题清单](./Algorithm/3-动态规划/)
  - [基础](./Algorithm/3-动态规划/00-基础.md)  `三要素(重复子问题、最优子结构、动态转移方程)`  `斐波那契数列`  `凑零钱问题`
  - [记忆化搜索](./Algorithm/3-动态规划/01-记忆化搜索.md)  `具备最优子结构`  `具备重叠子问题`  `memo记录子问题`  `子问题构成`
  - [线性 DP](./Algorithm/3-动态规划/02-线性DP.md)  `以i结尾的方案数`  `[0,1]范围内的最优解`  `打家劫舍`  `路径问题`
  - [背包 DP](./Algorithm/3-动态规划/03-背包DP.md)  `01背包`  `完全背包`  `多重背包`  `混合背包`  `分组背包`  `多维背包`  `树形背包`
  - [序列 DP](./Algorithm/3-动态规划/04-序列DP.md)  `无后效性`  `最长上升子序列(LIS)`  `最长公共子序列(LCS)`  `最大子数组和`  `LCS和LIS相互转化`
  - [区间 DP](./Algorithm/3-动态规划/05-区间DP.md)  `f(l,r)=max(f(l,k), f(k+1,r))+cost k in [l,r]`  `遍历方法`  `初始化(dp[i][i]=1)`  `返回(dp[0][i])`  `回文问题`  `时O(n^2)`
  - [树形 DP「hold on」](./Algorithm/3-动态规划/06-树形DP.md)  `后序遍历`  `打家劫舍III`
  - [状态压缩 DP](./Algorithm/3-动态规划/07-状态压缩DP.md)  `位运算`  `state = (1 << num) | state`  `((state >> num) & 1) == 0`  `n<15`
  - [数位 DP「hold on」](./Algorithm/3-动态规划/08-数位DP.md)
  - [股票问题](./Algorithm/3-动态规划/09-股票问题.md)  `状态机DP`
- **图论**  [🧾例题清单](./Algorithm/4-图论/)
  - [理论基础](./Algorithm/4-图论/01-理论基础.md)
  - [图的存储](./Algorithm/4-图论/02-图的存储.md)  `邻接表`  `邻接矩阵`  `类边`  `一维数组`  `链式前向星`
  - [DFS](./Algorithm/4-图论/03-DFS.md)  `回溯`  `剪枝`  `组合总和问题`  `子集划分问题`
  - [BFS](./Algorithm/4-图论/04-BFS.md)  `逐个遍历`  `逐层遍历`  `最短路径`  `双向bfs`  `多源bfs`
  - [拓扑排序](./Algorithm/4-图论/05-拓扑排序.md)  `有向无环图`  `学完a课才能学b课`
  - [最短路径](./Algorithm/4-图论/06-最短路径.md)  `Dijkstra、非负权、O(nlogn)`  `Floyd、多源、O(n^3)`  `Bellman-Ford、负环、O(n^2)`
  - [欧拉图](./Algorithm/4-图论/07-欧拉图.md)  `一笔画完整个图`
  - [A* 算法](./Algorithm/4-图论/08-A*算法.md)  `来源 bfs dijkstra`  `启发函数`
  - [二分图](./Algorithm/4-图论/09-二分图.md)
  - [内向基环树](./Algorithm/4-图论/10-内向基环树.md)  `从 i 向 arr[i] 连边`  `拓扑排序后，入度为1，为基环`  `求基环长度`
- **数学**  [🧾例题清单](./Algorithm/5-数学/)
  - [常用算法](./Algorithm/5-数学/常用算法/)  `num和arr互转`  `进制转换`  `向上取整`  `余数`  `高斯求和`  `快速幂`  `矩阵运算`  `最大公约数`  `最小公倍数`  `中位数`
  - [经典算法](./Algorithm/5-数学/经典算法/)  `蓄水池抽样算法`  `洗牌算法`  `约瑟夫环`  `投票算法`
- **系列题目**   [🧾例题清单](./Algorithm/6-系列题目/)
    - [括号问题](./Algorithm/6-系列题目/01-括号问题/)  `栈`  `递归剪枝`  `dp`  `bfs`  `贪心`
    - [组合问题](./Algorithm/6-系列题目/02-组合问题/)  `回溯`  `递归剪枝`  `去重`  `记忆化dfs`  `dp`
    - [算术问题](./Algorithm/6-系列题目/03-算术问题/)  `加法`  `除法`
    - [回文问题](./Algorithm/6-系列题目/04-回文问题/)  `左右双指针`  `中心扩散`
    - [子数组问题](./Algorithm/6-系列题目/05-子数组问题/)
    - [树的路径问题](./Algorithm/6-系列题目/06-树的路径问题/)
    - [设计数据结构](./Algorithm/1-数据结构/设计数据结构/)  `哈希集合/表`  `队列<->栈`  `LRU`  `LFU`

### *Chapter-2 [Skill](./Skill)*

> ctrl + c & ctrl + v 的一章

- [ASM](./Skill/ASM)
  - [RISC-V](./Skill/ASM/RISC-V)  `riscv asm manual`  `简介`  `通用寄存器和指令`  `扩展寄存器和指令`  `五级流水线`  `硬件模块`  `译码模块`  `ALU模块(执行计算)`  `branch模块(条件跳转)`  `load/store(访存)`  `CSR读写控制`
  - [x86-64](./Skill/ASM/x86)  `汇编`  `指令集`
- [C](./Skill/C)
  - [基础知识](./Skill/C/1-基础知识)  `数据类型`  `输入和输出`  `条件控制和循环`  `数组`  `函数`  `预处理`  `指针`  `结构体`  `文件操作`  `头文件`
  - [C语言内存](./Skill/C/2-C语言内存)  `虚拟内存`  `内存对齐`  `内存分页`  `MMU`  `内存模型`  `内核模式`  `用户模式`  `栈`  `堆`  `动态内存分配`  `内存池`  `野指针`  `内存泄漏`  `函数调用`
- [C++](./Skill/C++)
  - [基础知识](./Skill/C++/1-基础知识)  `GCC`  `数据类型`  `条件`  `循环`  `运算符`  `函数`  `char`  `string`  `数组`  `指针`  `shared_ptr`  `引用`  `struct`  `namespace`  `头文件`  `链接库`  `异常处理`  `输入输出流`  `文件操作`  `多文件编程`
  - [面向对象](./Skill/C++/2-面向对象)  `类和对象`  `继承和派生`  `多态与虚函数`  `运算符重载`  `模版和范型`
  - [标准模版库](./Skill/C++/3-标准模板库)  `vector`  `deque`  `multimap`  `multiset`  `unordered_map`  `unordered_set`  `queue`  `priority_queue`  `algorithm`
- [Golang](./Skill/Golang)
  - [基础知识](./Skill/Golang/1-基础知识)   `string`  `slice`  `map`  `struct`  `指针`  `interface`
  - [Go语言并发](./Skill/Golang/2-Go语言并发)  `goroutine`  `chan`  `WaitGroup`  `如何实现`  `sync.Mutex`  `sync.RWMutex`  `atomic`  `死锁`
  - [进阶知识](./Skill/Golang/3-进阶知识)  `常见GC算法`  `Go GC`  `观察GC`  `内存泄漏`  `GC调优`
  - [实用函数](./Skill/Golang/4-实用函数)  `计时器`
- [Python](./Skill/Python)  `str`  `list`  `set`  `tuple`  `dict`  `defaultdict`  `deque`  `bisect`  `heapq`  `SortedList`  `__lt__`  `CPython架构`  `python为什么慢`
- [Linux「挖坑」](./Skill/Linux)
  - [File system](./Skill/Linux/filesystem)  `overlayfs`  `shared-subtrees`  `快照和备份`
- [Android「挖坑」](./Skill/Android)
- [工具链](./Skill/工具链)  `工具`  `网站`  `vscode`  `git`  `vim`  `gdb`  `gcc`  `tmux`  `make`
- [常用 CLI](./Skill/常用CLI)  `docker`  `k8s`  `ceph`
- [Markdown](./Skill/Markdown/README.md)
- [LaTeX](./Skill/LaTeX)
  - [数学符号](./Skill/LaTeX/1-数学符号.md)  `运算符`  `关系符`  `定界符`  `箭头`  `希腊字母`  `常用符号`  `重音符`
  - [公式格式](./Skill/LaTeX/2-公式格式.md)  `求和`  `分数`  `大括号`  `等号对齐`
- [Mermaid](./Skill/Mermaid/README.md)  `流程图`  `时序图`  `甘特图`  `类图`  `状态图`  `饼图`  `用户体验旅程图`

### *Chapter-3 [Knowledge](./Knowledge)*

> 下述大多来源教科书，~~都是些夸夸其谈、老旧的、假的知识~~。

- [IC](./Knowledge/01-IC)  `design`  `fabrication`  `package`  `EDA`  `FPGA`  `Verilog`
- [计算机组成](./Knowledge/02-计算机组成)
  - [序](./Knowledge/02-计算机组成/README.md)  `大纲`  `程序是如何在计算机里跑起来的`
  - [计算机系统概述](./Knowledge/02-计算机组成/01-计算机系统概述.md)  `软硬件分类及发展`  `冯•诺依曼结构`  `工作过程`  `性能指标`
  - [数据的表示和运算](./Knowledge/02-计算机组成/02-数据的表示和运算.md)  `数制`  `定点数`  `浮点数`  `算术逻辑单元`
  - [存储系统](./Knowledge/02-计算机组成/03-存储系统.md)  `分类`  `性能指标`  `层次化结构`  `SRAM(cache)`  `DRAM(内存)`  `ROM(闪存、固态)`  `MM组成和使用`  `Cache`  `虚拟存储器`
  - [指令系统](./Knowledge/02-计算机组成/04-指令系统.md)  `指令(操作码+地址码)`  `指令寻址`  `数据寻址`  `指令集`  `CISC`  `RISC`
  - [中央处理器](./Knowledge/02-计算机组成/05-中央处理器.md)  `CPU(运算器+控制器)`  `指令执行`  `数据通路`  `硬布线控制器`  `微程序控制器`  `指令流水线`
  - [总线](./Knowledge/02-计算机组成/06-总线.md)  `片内、系统、通信总线`  `性能指标`  `总线仲裁`  `传输和定时`  `总线标准`
  - [输入输出系统](./Knowledge/02-计算机组成/07-输入输出系统.md)  `外部设备`  `IO接口`  `IO方式(查询、中断、DMA)`
  - [扫盲 cpu gpu tpu npc](./Knowledge/02-计算机组成/08-扫盲cpu-gpu-tpu-npu.md)
  - [X86 体系结构](./Knowledge/02-计算机组成/09-X86体系结构.md)
- [操作系统](./Knowledge/03-操作系统)
  - [计算机系统概述](./Knowledge/03-操作系统/01-计算机系统概述.md)  `目的(管理、调度软硬资源、提供接口)`  `特征(并发、共享、虚拟、异步)`  `分类`  `运行环境(内核态、用户态)`  `中断`  `系统调用`
  - [进程管理](./Knowledge/03-操作系统/02-进程管理.md)  `进程(程序段、数据段、进程控制块)`  `目的(并发、共享)`  `进程通信`  `线程(ID、计数器、寄存器集合)`  `目的(减少开销)`  `实现方式(用户级、内核级)`  `处理机调度`  `进程同步`  `互斥`  `死锁`  `饥饿`
  - [进程 & 线程 & 协程](./Knowledge/03-操作系统/进程&线程&协程.md)  `时间角度`  `资源角度`
  - [内存管理](./Knowledge/03-操作系统/03-内存管理.md)  `目的(并发)`  `覆盖与交换`  `连续分配`  `非连续分配(分页存储)`  `分段存储`  `虚拟内存`  `局部性原理(时间、空间)`
  - [文件管理](./Knowledge/03-操作系统/04-文件管理.md)  `文件结构`  `目录结构`  `共享`  `保护`  `文件系统结构`  `目录实现`  `文件实现`  `磁盘(结构、调度、管理)`
  - [输入输出管理](./Knowledge/03-操作系统/05-输入输出管理.md)  `IO设备`  `IO控制方式`  `IO层次`  `设备分配、回收`  `Cache(缓存)`  `Buffer(缓冲区)`
  - [虚拟化](./Knowledge/03-操作系统/06-虚拟化.md)
- [计算机网络](./Knowledge/04-计算机网络)
  - [计算机网络体系结构](./Knowledge/04-计算机网络/01-计算机网络体系结构.md)  `组成`  `功能`  `分类`  `性能指标`  `OSI模型(7层)`  `TCP/IP模型(4层)`  `5层协议体系`  `报文、包、帧等概念`
  - [物理层](./Knowledge/04-计算机网络/02-物理层.md)  `层一`  `传输比特流`  `数字信道(基带信号)`  `模拟信道(宽带信号)`  `奈奎斯特定理(码元极限传输速率)`  `香农定理(数据极限传输速率)`  `编码与调制PSK`  `电路、报文、分组交换`  `数据报、虚电路服务`  `传输介质`  `中继器`  `集线器`
  - [数据链路层](./Knowledge/04-计算机网络/03-数据链路层.md)  `层二(mac层)`  `数据逻辑上无差错`  `链路管理`  `组帧`  `差错控制`  `流量控制(滑窗)`  `介质访问控制(多路复用、随机访问CSMA)`  `局域网(以太网)`  `IEEE 802.3/11`  `网卡(MAC地址)`  `广域网(交换机+链路)`  `网桥`  `以太网交换机`
  - [网络层](./Knowledge/04-计算机网络/04-网络层.md)  `层三(IP层)`  `功能(异构互联、分组转发、拥塞控制)`  `路由算法`  `IPv4`  `IP数据报`  `IP地址`  `子网`  `IPv6`  `路由协议`  `IP组播`  `移动IP`  `路由器`
  - [传输层](./Knowledge/04-计算机网络/05-传输层.md)  `功能(进程间通信)`  `端口`  `socket(嵌套字)`  `UDP(无连接)`  `TCP(连接)`  `报文段`  `TCP建立连接(三次挥手)`  `TCP释放连接(四次握手)`  `可靠传输`  `流量控制`  `拥塞控制`
  - [应用层](./Knowledge/04-计算机网络/06-应用层.md)  `网络应用模型(C/S、P2P)`  `DNS`  `FTP`  `电子邮件(SMTP、POP3/IMAP)`  `万维网(HTTP)`  `Cookie`
  - [5G 网络架构](./Knowledge/04-计算机网络/07-5G网络架构.md)  `场景`  `网络架构`  `接口`  `协议栈`  `核心网`  `接入网`  `组网`  `层二(mac数据面)`  `层三(mac控制面)`
  - [socket](./Knowledge/04-计算机网络/08-socket.md)
- [容器技术](./Knowledge/05-容器技术)
  - [docker 原理](./Knowledge/05-容器技术/1-docker原理.md)  `Namespace(进程、网络、存储)`  `CGgroups`  `UnionFS`
  - [kubernetes 原理](./Knowledge/05-容器技术/2-kubernetes原理.md)  `介绍`  `设计`  `架构(master、worker)`  `重要概念(对象、Spec、Status)`
  - [kubernetes 对象详解](https://doongz.gitbook.io/notes/knowledge/05-rong-qi-ji-shu/kubernetes-dui-xiang-xiang-jie)  `pod`  `service`  `volume`  `replicaSet`  `garbage collector`  `deployment`  `statefulSet`  `daemonSet`  `job&cronJob`
  - [kubernetes 定制特性](./Knowledge/05-容器技术/3-kubernetes定制特性.md)  `扩展接口`  `容器接口(网络插件、存储插件、运行时接口)`  `设备插件`  `调度框架`
  - [kubernetes 问题 & 局限性](./Knowledge/05-容器技术/4-kubernetes问题&局限性.md)  `集群管理(水平扩展性、多集群管理)`  `应用场景(应用分发、批处理调度、硬多租户)`
  - [kubernetes 集群联邦 & 资源分发](./Knowledge/05-容器技术/5-kubernetes集群联邦&资源分发.md)  `kubefed`  `karmada`
  - [kubernetes 贡献指南](./Knowledge/05-容器技术/6-kubernetes贡献指南.md)  `SIG`  `KEP`  `期望(项目设计、分布式协作、影响力)`  `操作指南(阅读源码、静态检查、项目管理)`
- [数据 & 存储「未完工」](./Knowledge/06-数据存储)
  - 设计数据密集型应用「未完工」
  - 数据库「未完工」  `关系型数据库`  `NoSQL`
  - 消息队列「未完工」
  - 分布式存储「未完工」 `ceph`

### *Chapter-4 [Math](./Math)*

> 为什么要去学*牛顿-莱布尼茨* 时代的微积分？因为在 2016 年，身体里的编程力量没有觉醒。
>
> ~~其实是为了考研，令人欣慰的是考了满分~~

- [微积分](./Math/微积分)
  - [极限](./Math/微积分/1-极限.md)
  - [一元函数微积分](./Math/微积分/2-一元函数微积分.md)
  - [多元函数微分学](./Math/微积分/3-多元函数微分学.md)
  - [二重积分](./Math/微积分/4-二重积分.md)
  - [微分方程](./Math/微积分/5-微分方程.md)
- [线性代数](./Math/线性代数)
  - [行列式](./Math/线性代数/1-行列式.md)
  - [矩阵](./Math/线性代数/2-矩阵.md)
  - [向量组与方程组](./Math/线性代数/3-向量组与方程组.md)
  - [特征与二次型](./Math/线性代数/4-特征与二次型.md)

## *Writing Standard*

[Generate SUMMARY.md](https://github.com/imfly/gitbook-summary) for gitbook:

```shell
$ book sm
```

naming rule:

```
25-<技巧>-题目.md
面试题-17-16-<技巧>-题目.md
剑指Offer-09-<技巧>-题目.md
```

## *Statement*

**Publish**  [https://doongz.gitbook.io/notes/](https://doongz.gitbook.io/notes/)

**Reference**  [oi-wiki](https://oi-wiki.org) | [leetcode](https://leetcode.cn/problemset/all/) | [codeforces](https://codeforces.com/) | [bilibili](https://www.bilibili.com/) |  [luogu](https://www.luogu.com.cn) | [c-biancheng](http://c.biancheng.net/) | [geeksforgeeks](https://www.geeksforgeeks.org/) | [draveness](https://draveness.me/) | [宫水三叶](https://github.com/SharingSource/LogicStack-LeetCode) | [CS自学指南](https://github.com/pkuflyingpig/cs-self-learning/)

**License** [CC-BY-SA-4.0 License](https://github.com/doongz/notes/blob/main/LICENSE)

<p>
    <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
</p>


---

***Thanks Your Star***

![Star History Chart](https://api.star-history.com/svg?repos=doongz/notes&type=Date)
