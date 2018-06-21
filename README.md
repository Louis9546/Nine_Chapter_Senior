Session 1   Follow-Up Questions I
----------------------------------------------------------------------------------------------------------------------------

* Two Sum
* Two sum II
* Triangle Count
* Kth Smallest Number In Sorted Matrix
* Kth Largest in N Arrays
* Kth Smallest Sum In Two Sorted Arrays

Session 2   Data Structure I
----------------------------------------------------------------------------------------------------------------------------

* Union Find 并查集
* Find the Connected Component in the Undirected Graph
* Find the Weak Connected Component in the Directed Graph
* Google Interviewer: Number of Islands
* Google Interviewer: Number of Islands II
* Facebook Interviewer: Graph Valid Tree
* Surrounded Regions

* Trie 字典树
  * Snapchat Interviewer: Implement Trie

* Hash vs Trie
  * Microsoft Interviwer: Word Search II
  * Snapchat Interviewer: Add and Search Word

* Typeahead 搜索引擎
* 设计算法获得IP到城市的Map：http://www.jiuzhang.com/qa/262/

* Sweep-Line 扫描线
  * Amazon Interviewer: Number of Airplane in the sky

* Summary:
  * Union Find: 	集合合并，查找元素在集合里面
  * Trie: 			快速找到一个元素，一个字母一个字母查找
  * Sweep-line: 	区间拆分

Session 3   Data Structure II
----------------------------------------------------------------------------------------------------------------------------

* Heap 堆: PriorityQueue
  * Trapping Rain Water
  * Trapping Rain Water II

* 小技巧: 矩阵从外向内遍历技巧
    * Building Outline

* Question? 重复元素怎么办？
    * Data Stream Median
    * Sliding Window Median

* 小技巧
    * Sliding Window的题目可以拆解为下面两步：（1）加一个元素；（2）删一个元素.

* Deque 双端队列
    * Sliding Window Maximum
    * Sliding Window Matrix Maximum


Session 4   Two Pointers
----------------------------------------------------------------------------------------------------------------------------

1. 对撞型或者相会型: 

    __Two sum类__
    1. Two sum II
    2. Triangle Count
    3. Trapping Rain Water
    4. Container With Most Water
    5. Sum Closest
    6. 4 Sum
    7. 3 Sum
    8. k sum

    __Partition类__
    1. Kth Largest Element [Quick Select / Quick Sort]
    2. Nuts & Bolts Problem
    3. Sort Colors
    4. Partition Array by Odd and Even
    5. Sort Letters by Case
    6. Valid Palindrome
    7. Wiggle sort II

2. 前向型或者追击型
    __窗口类__
    1. Minimum Size Subarray Sum
    2. Longest Substring Without Repeating Characters
    3. Minimum Window Substring
    4. Longest Substring with At Most K (two) Distinct Characters
    5. Remove Nth Node From End of List

    __快慢类__
    1. Find the Middle of Linked List
    2. Linked List Cycle I
    3. Linked List Cycle II

3. 两个数组两个指针（并行型）

两个数组各找一个元素，使得和等于target：（1）找一种；（2）找全部种类.

The Smallest Difference

Merge Two Sorted Lists


Session 5   Dynamic Programming I
----------------------------------------------------------------------------------------------------------------------------

1. 滚动数组优化

    f[i] = max(f[i-1], f[i-2] + A[i]); 转换为 f[i%2] = max(f[(i-1)%2]和 f[(i-2)%2]);
    1. House Robber
    2. House Robber II
    3. Maximal Square

    __小技巧__
    1. 网格类的题目
    2. 正方形用右下角作为定位角
    3. 长方形可以用左上角和右下角作为定位角

    __二维滚动数组相关题目__
    1. Unique Paths
    2. Minimum Path Sum
    3. Edit Distance

2. 记忆化搜索
    1. Longest Increasing Subsequence
    2. Longest Increasing Continuous Subsequence 2D

    __博弈类DP__
    1. Coins in a line
    2. Coins in a line II
    3. Coins in a line III


Session 6   Dynamic Programming II
----------------------------------------------------------------------------------------------------------------------------

1. 区间类DP
    __特点__
    1. 求一段区间的解max/min/count
    1. 转移方程通过区间更新
    1. 从大到小的更新

Stone Game

Burst Ballons

Scramble String

coin in a line III

2. 背包类DP
BackPack

BackPack IV

BackPack II

K Sum

Minimum Adjustment Cost


Session 7   Follow-Up Questions II
----------------------------------------------------------------------------------------------------------------------------

Find Peak Element

Find Peak Element II
    __第K大问题__
    1. Kth Largest Element
    2. Kth Smallest Number In Matrix
    3. Kth Smallest Number In Two Arrays
    4. Subarray Sum
    5. Submatrix Sum
    6. Subarray Sum II
    __循环连续子序列__
    1. Continuous Subarray Sum
    2. Continuous Subarray Sum II
    __旋转排序__
    1. Wiggle Sort
    2. Wiggle Sort II
