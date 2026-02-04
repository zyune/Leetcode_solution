# Leetcode_solution


All the code here is according to [labuladong](https://github.com/labuladong/fucking-algorithm), but a python version. If you were a labuladong reader , but you prefer to use python as your weapon on leetcode. You are in the right battle field.

I build this repo initially in this [organization](https://github.com/Portland-Chinese-folks-PoP-leetcode/Leetcode_solution), If you want to check some template written in python. Go to [issue tab](https://github.com/Portland-Chinese-folks-PoP-leetcode/Leetcode_solution/issues) . If you want to check the solution of certain leetcode question, just click on solution.

Rule No.1

- Don't be a coward before algorithem problems. Show me your gut, and let's fuck algorithem.

![output](img/fight_club.png)

Rule No.2

- Talk is cheap, Code is valuable. So Shut The Fuck Up. 《话越多越菜》

![output](img/Pulp-Fiction.jpeg)

复习 第一轮()

# 复习的第一个周期（3 天）实际用时 4 天

#### single linked list

- [merge-k-sorted-lists](https://leetcode.cn/problems/merge-k-sorted-lists/submissions/) [**solution**](linked_list/merge-k-sorted-lists-priorityqueue-version.py)
- [merge-two-sorted-lists](https://leetcode.com/problems/merge-two-sorted-lists/) [**solution**](linked_list/merge-two-sorted-lists.py)
- [remove-nth-node-from-end-of-list](https://leetcode.cn/problems/remove-nth-node-from-end-of-list/submissions/) [**solution**](linked_list/remove-nth-node-from-end-of-list.py) 先后指针
- [middle-of-the-linked-list](https://leetcode.cn/problems/middle-of-the-linked-list/submissions/) [**solution**](linked_list/middle-of-the-linked-list.py) 快慢指针
- [linked-list-cycle](https://leetcode.cn/problems/linked-list-cycle/submissions/) [**solution**](linked_list/linked-list-cycle.py) 快慢指针
- [linked-list-cycle-ii](https://leetcode.cn/problems/linked-list-cycle-ii/submissions/) [**solution**](linked_list/linked-list-cycle-ii.py) 第一次相遇 fast 和 slow 速度不同，相遇后 slow 退回 head，跑到再次相遇（此时快慢速度一样）
- [intersection-of-two-linked-lists](https://leetcode.cn/problems/intersection-of-two-linked-lists/) [**solution**](linked_list/intersection-of-two-linked-lists.py)

#### 反转 single linked list

- [reverse-linked-list](https://leetcode.cn/problems/reverse-linked-list/) [**solution**](linked_list/reverse-linked-list.py) 递归实现反转单链表(模板)， 需要背熟
- [reverse-linked-list-ii](https://leetcode.cn/problems/reverse-linked-list-ii/) [**solution**](linked_list/reverse-linked-list-ii.py) python 的实现不太一样 需要背熟
- [reverse-nodes-in-k-group](https://leetcode.cn/problems/reverse-nodes-in-k-group/submissions/) [**solution**](linked_list/reverse-nodes-in-k-group.py) 用迭代实现反转

#### 回文串 |<—— left right ——>|

- [valid-palindrome](https://leetcode.cn/problems/valid-palindrome/submissions/) [**solution**](string/valid-palindrome.py)
- [palindrome-linked-list](https://leetcode.cn/problems/palindrome-linked-list/submissions/) [**solution 1**](linked_list/palindrome-linked-list.py) [**solution 2**](linked_list/palindrome-linked-list-v2.py)

#### binary |left——> <——right|

- [binary-search](https://leetcode.cn/problems/binary-search/) [**solution**](binary/binary-search.py)
- [find-first-and-last-position-of-element-in-sorted-array](https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/) [**solution**](binary/find-first-and-last-position-of-element-in-sorted-array-v2.py)
- [search-insert-position](https://leetcode.cn/problems/search-insert-position/) [**solution**](binary/search-insert-position.py)

#### double pointer 双指针

- [remove-duplicates-from-sorted-array](https://leetcode.cn/problems/remove-duplicates-from-sorted-array/) [**solution**](doublePointer/remove-duplicates-from-sorted-array.py) 原地修改数组 (快慢)
- [remove-duplicates-from-sorted-list](https://leetcode.cn/problems/remove-duplicates-from-sorted-list/submissions/) [**solution**](doublePointer/remove-duplicates-from-sorted-list.py) 原地修改链表 (快慢)
- [remove-element](https://leetcode.cn/problems/remove-element/) [**solution**](doublePointer/remove-element.py) 原地修改数组 (快慢)
- [move-zeroes](https://leetcode.cn/problems/move-zeroes/) [**solution**](doublePointer/moveZeroes.py) 原地修改数组 (快慢)
- [two-sum-ii-input-array-is-sorted](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/) [**solution**](doublePointer/two-sum-ii-input-array-is-sorted.py) （两边向中间 move 的指针）
- [reverse-string](https://leetcode.cn/problems/reverse-string) [**solution**](doublePointer/reverse-string.py)(两边向中间 move 的指针)
- [longest-palindromic-substring](https://leetcode.cn/problems/longest-palindromic-substring/) [**solution**](doublePointer/longest-palindromic-substring.py)(中间向两边 move 的指针)

#### slidng window(典型快慢指针，快慢中间就是所谓的窗口)，用于结局子串问题

- [minimum-window-substring](https://leetcode.cn/problems/minimum-window-substring) [**solution**](slidingWindow/minimum-window-substring.py)
- [permutation-in-string](https://leetcode.cn/problems/permutation-in-string) [**solution**](slidingWindow/permutation-in-string.py)
- [find-all-anagrams-in-a-string](https://leetcode.com/problems/find-all-anagrams-in-a-string/) [**solution**](slidingWindow/find-all-anagrams-in-a-string.py)
- [longest-substring-without-repeating-characters](https://leetcode.cn/problems/longest-substring-without-repeating-characters) [**solution**](slidingWindow/longest-substring-without-repeating-characters.py)

#### Nsum 这玩意就得背熟，尤其里面那个 NsumTarget(nums,n,start,target)函数，是真的难打

- [two-sum](https://leetcode.cn/problems/two-sum/) [**solution**](N-sum/two-sum.py)
- [two-sum-ii-input-array-is-sorted](https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/) [**solution**](doublePointer/two-sum-ii-input-array-is-sorted.py)
- [3sum](https://leetcode.cn/problems/3sum/) [**solution**](N-sum/threeSum.py)
- [4sum](https://leetcode.cn/problems/4sum/) [**solution**](N-sum/4sum.py)

#### 前缀和/积 rangeSum。 本质是用一个新数组 preSum 来存储元数组的累加和或者累加积，以使得算法的时间复杂度打到 O(1),when we creating the presum array, the length of row or column is always 1 bigger than the original one

- [range-sum-query-immutable](https://leetcode.cn/problems/range-sum-query-immutable/) [**solution**](rangesum前缀/range-sum-query-immutable.py)
- [range-sum-query-2d-immutable](https://leetcode.cn/problems/range-sum-query-2d-immutable/) [**solution**](rangesum前缀/range-sum-query-2d-immutable.py)

#### 差分数组 difference array

- [range-addition](https://leetcode.cn/problems/range-addition/submissions/) [**solution**](differenceArray/range-addition.py)
- [corporate-flight-bookings](https://leetcode.cn/problems/corporate-flight-bookings/) [**solution**](differenceArray/corporate-flight-bookings.py)
- [car-pooling](https://leetcode.cn/problems/car-pooling/submissions/) [**solution**](differenceArray/car-pooling.py)

# 复习的第二轮 (费城回来以后)

## 二叉搜索树（BST）

- 对于 BST 的每一个节点 node，左子树节点的值都比 node 的值要小，右子树节点的值都比 node 的值大。
- 对于 BST 的每一个节点 node，它的左侧子树和右侧子树都是 BST。
- BST 中序遍历就是升序排序结果」这个性质，每次寻找第 k 小的元素都要中序遍历一次，最坏的时间复杂度是 O(N)

#### [二叉搜索树\_特性篇](https://labuladong.github.io/algo/2/19/39/) 下面三题都是中序

- [kth-smallest-element-in-a-bst](https://leetcode.com/problems/kth-smallest-element-in-a-bst/) [**Solution**](Binary_tree/二叉搜索树_特性_中序/convert-bst-to-greater-tree.py) travese 的思路
- [convert-bst-to-greater-tree](https://leetcode.com/problems/convert-bst-to-greater-tree/) [**Solution**](Binary_tree/二叉树_特性_中序/convert-bst-to-greater-tree.py) travese 的思路
- [binary-search-tree-to-greater-sum-tree](https://leetcode.cn/problems/binary-search-tree-to-greater-sum-tree/) [**Solution**](relative_path) 和上一题一模一样

#### [二叉搜索树\_基操篇](https://labuladong.github.io/algo/2/19/40/) 判断 BST 的合法性、增、删、查。其中「删」和「判断合法性」略微复杂

- [validate-binary-search-tree](https://leetcode.cn/problems/validate-binary-search-tree/) [**Solution**](Binary_tree/二叉搜索树_基操篇/validate-binary-search-tree.py) 分解问题的思路，使用尾递归 返回值。None 的时候返回 True。注意**参数的传递** 很有意思。
- [delete-node-in-a-bst](https://leetcode.cn/problems/delete-node-in-a-bst/) [**Solution**](Binary_tree/二叉搜索树_基操篇/delete-node-in-a-bst.py) 当删除节点有两个子节点， A 必须找到左子树中最大的那个节点，或者右子树中最小的那个节点来接替自己。最后需要返回 root
- [search-in-a-binary-search-tree](https://leetcode.cn/problems/search-in-a-binary-search-tree/) [**Solution**](Binary_tree/二叉搜索树_基操篇/search-in-a-binary-search-tree.py)
- [insert-into-a-binary-search-tree](https://leetcode.cn/problems/insert-into-a-binary-search-tree/) [**Solution**](Binary_tree/二叉搜索树_基操篇/insert-into-a-binary-search-tree.py) 最后也需要返回 root

#### [二叉搜索树\_构造篇](https://labuladong.github.io/algo/2/19/41/)

- [unique-binary-search-trees-ii](https://leetcode.cn/problems/unique-binary-search-trees-ii/) [**Solution**](Binary_tree/二叉搜索树_构造篇/unique-binary-search-trees-II.py) 结合 后序 二叉树（子问题的思路） 动态规划 memo 的 base case。子问题的思路
- 1 穷举 root 节点的所有可能。2、递归构造出左右子树的所有合法 BST。 3、给 root 节点穷举所有左右子树的组合。
- [unique-binary-search-trees](https://leetcode.cn/problems/unique-binary-search-trees/) [**Solution**](Binary_tree/二叉搜索树_构造篇/unique-binary-search-trees.py) 这一题的本质是特殊的动态规划 memorization（一开始我以为是回溯，但不是）

# 二叉树

#### [二叉树\_纲领](https://labuladong.github.io/algo/2/19/33/)

- [binary-tree-preorder-traversal](https://leetcode.com/problems/binary-tree-preorder-traversal/) [**Solution**](Binary_tree/二叉树_纲领/binary-tree-preorder-traversal.py)
- [diameter-of-binary-tree](https://leetcode.com/problems/diameter-of-binary-tree/) [**Solution**](Binary_tree/二叉树_纲领/diameter-of-binary-tree.py) 一个 root 的 diameter 是左边最深+右边最深 需要在 class 里定义一个 diameter
- [maximum-depth-of-binary-tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/) [**Solution**](Binary_tree/二叉树_纲领/maximum-depth-of-binary-tree.py) 找最深 在后序的位置用 max，尾递归

#### [二叉树\_思路](https://labuladong.github.io/algo/2/19/34/)

- [flatten-binary-tree-to-linked-list](https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/) [**Solution**](Binary_tree/二叉树_思路/flatten-binary-tree-to-linked-list.py) (分解问题)1、将 root 的左子树和右子树拉平。 2、将 root 的右子树接到左子树下方，然后将整个左子树作为右子树（虽然没有 return value 但仍然属于分解问题）
- [populating-next-right-pointers-in-each-node](https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/) [**Solution**](Binary_tree/二叉树_思路/populating-next-right-pointers-in-each-node.py) （遍历）这题用到完美二叉树，用 traverse 但是参数定义不一样，很有意思。同样执行转换的位置在前序或者后序都不影响
- [invert-binary-tree](https://leetcode.cn/problems/invert-binary-tree/) [**Solution**](Binary_tree/二叉树_思路/invert-binary-tree.py) （遍历）这题的左右子树转换的代码位置在后序或者前序 并不影响结果（利用第一种遍历思路）

#### [二叉树\_构造](https://labuladong.github.io/algo/2/19/35/) 基本构造都用分解问题

- [construct-binary-tree-from-preorder-and-inorder-traversal](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) [**Solution**](Binary_tree/二叉树_构造/construct-binary-tree-from-preorder-and-inorder-traversal.py) 第二种思路 找到中序的 index，构造 build 函数，参数很多，第二次传参的中序 start 和 end 只和 index 有关 。一定要注意，传入的参数是 index！
- [construct-binary-tree-from-inorder-and-postorder-traversal](https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/) [**Solution**](Binary_tree/二叉树_构造/construct-binary-tree-from-inorder-and-postorder-traversal.py) 和上一题的思路一样
- [maximum-binary-tree](https://leetcode.cn/problems/maximum-binary-tree/) [**Solution**](Binary_tree/二叉树_构造/maximum-binary-tree.py) 定义 build 函数 def build(nums,lo,hi):
- [construct-binary-tree-from-preorder-and-postorder-traversal](https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/) [**Solution**](Binary_tree/二叉树_构造/construct-binary-tree-from-preorder-and-postorder-traversal.py) 这一题可以有多种答案，利用 prestart 的后一个元素，所以需要多一个判断当 prestart=preend 的时候 直接 return TreeNode(preorder[prestart])
- [construct-binary-search-tree-from-preorder-traversal](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal) [**Solution**](Binary_tree/二叉树_构造/construct-binary-search-tree-from-preorder-traversal.py) build(preorder,start,end) 用一个 while 循环找到第一个比 prestart 大的元素的 index

#### [二叉树\_序列化](https://labuladong.github.io/algo/2/19/36/)

- [serialize-and-deserialize-binary-tree](https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/) [**Solution 1**](Binary_tree/二叉树_序列化/serialize-and-deserialize-binary-tree.py) 递归解法绝对是 后序的大妙用
- [**Solution 2**](Binary_tree/二叉树_序列化/BFS-serialize-and-deserialize-binary-tree.py)
  每一个非空节点都会对应两个子节点，那么反序列化的思路也是用队列进行层级遍历，同时用索引 i 记录对应子节点的位置：
  ![output](img/bfs序列化二叉树.png)

#### [二叉树\_后序](https://labuladong.github.io/algo/2/19/37/)

- [find-duplicate-subtrees](https://leetcode.cn/problems/find-duplicate-subtrees/) [**Solution**](Binary_tree/二叉树_后序/find-duplicate-subtrees.py)

## 暴力穷举

#### backtracking 回溯

[回溯算法解题套路框架](https://labuladong.github.io/algo/4/29/103/)

- [Template](backtracking/backtrack_template.py)
- [n-queens](https://leetcode.cn/problems/n-queens/) [**Solution**](backtracking/n-queens.py)
- [permutations](https://leetcode.cn/problems/permutations/) [**Solution**](backtracking/permutations.py) 用了 printindent 的操作(这个套路很骚，适用于所有递归)

[经典回溯算法：集合划分问题](https://labuladong.github.io/algo/4/29/104/)

- [partition-to-k-equal-sum-subsets](https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/) [**Solution**](backtracking/partition-to-k-equal-sum-subsets.py)

[回溯算法秒杀所有排列/组合/子集问题](https://labuladong.github.io/algo/4/29/105/)

- [permutations](https://leetcode.cn/problems/permutations/) [**Solution**](backtracking/permutations.py) 无重复 不可复选
- [subsets](https://leetcode.cn/problems/subsets/) [**Solution**](backtracking/subsets.py) 无重复 不可复选
- [subsets-ii](https://leetcode.cn/problems/subsets-ii/) [**Solution**](backtracking/subsets-ii.py) 有重复 不可复选
- [permutations-ii](https://leetcode.cn/problems/permutations-ii/) [**Solution**](backtracking/permutations-ii.py) 有重复 不可复选
- [combinations](https://leetcode.cn/problems/combinations/) [**Solution**](backtracking/combinations.py) 无重复 不可复选
- [combination-sum](https://leetcode.cn/problems/combination-sum/) [**Solution**](backtracking/combination-sum.py) 无重复 可复选
- [combination-sum-ii](https://leetcode.cn/problems/combination-sum-ii/) [**Solution**](backtracking/combination-sum-ii.py) 可重复 不可复选
- [combination-sum-iii](https://leetcode.cn/problems/combination-sum-iii) [**Solution**](backtracking/combination-sum-iii.py) 这题我还没做

[回溯算法最佳实践：括号生成](https://labuladong.github.io/algo/4/29/108/)

- [generate-parentheses](https://leetcode.cn.com/problems/generate-parentheses/submissions/) [**Solution**](backtracking/generate-parentheses.py)

#### [islands](https://labuladong.github.io/algo/4/29/106/) (岛屿 也就是 flood fill)

- a simple framework demo for island [**Solution**](islands/island_framework.py)
- [number-of-islands](https://leetcode.cn/problems/number-of-islands/) [**Solution**](islands/number-of-islands.py) ### 最简单的 直接淹
- [max-area-of-island](https://leetcode.cn/problems/max-area-of-island/) [**Solution**](islands/max-area-of-island.py)
- [number-of-enclaves](https://leetcode.cn/problems/number-of-enclaves/) [**Solution**](islands/number-of-enclaves.py)
- [number-of-closed-islands](https://leetcode.cn/problems/number-of-closed-islands/) [**Solution**](islands/number-of-closed-islands.py)
- [count-sub-islands](https://leetcode.cn/problems/count-sub-islands/) [**Solution**](islands/count-sub-islands.py)
- [number-of-distinct-islands](https://leetcode.cn/problems/number-of-distinct-islands/) [**Solution**](islands/number-of-distinct-islands.py)

#### [BFS](https://labuladong.github.io/algo/4/29/109/)

- [BFS_template](BFS/BFS_template.py)
- [minimum-depth-of-binary-tree](https://leetcode.cn/problems/minimum-depth-of-binary-tree/) [**Solution**](BFS/minimum-depth-of-binary-tree.py)
- [open-the-lock](https://leetcode.cn/problems/open-the-lock/) [**Solution**](BFS/open-the-lock.py)
- [sliding-puzzle](https://leetcode.cn/problems/sliding-puzzle/) [**Solution**](BFS/sliding-puzzle.py)

#### Graph

- [adjacency list depth first search template](Graph图/graph_template.py) 简单邻接表图深度遍历的 python 实现模板
- [all-paths-from-source-to-target](https://leetcode.cn/problems/all-paths-from-source-to-target/submissions/) [**solution**](Graph图/all-paths-from-source-to-target.py) 这一题是邻接表

#### section_name

- [question_name](leetcode_link) [**Solution**](relative_path)

## DP

- [fibonacci-number](https://leetcode.cn/problems/fibonacci-number/) [**Solution**](DP/fibonacci-number.py)
- [coin-change](https://leetcode.com/problems/coin-change/submissions/) [**Solution memo**](DP/coin_change_memo.py) [**Solution table**](DP/coin_change_table.py)
- [longest-increasing-subsequence](https://leetcode.cn/problems/longest-increasing-subsequence/) [**Solution**](DP/lengthOfLIS.py) 子序列问题，注意子序列 并不是连续的 for i in range(1,len(dp)):
  for j in range(0,i): 两个 for 循环 复杂度是 n 方
- [russian-doll-envelopes](https://leetcode.cn/problems/russian-doll-envelopes/) [**Solution**](DP/russian-doll-envelopes.py) 这个的思路是先用 lambda 排序 在进行 LIS
- [maximum-subarray](https://leetcode.cn/problems/maximum-subarray/) [**Solution**](DP/maximum-subarray.py) 这个是 subset 区别这个和 subsequence

#### 一维

#### 二维

#### memorization

#### Test for donald
