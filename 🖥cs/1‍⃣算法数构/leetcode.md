|     | 递归  | 分治     | 贪心    | 动态规划          |
| --- | --- | ------ | ----- | ------------- |
|     |     | 子问题相对立 | 普通递归？ | 子问题相重叠        |
|     |     |        |       | 相比递归，只是多了保存结果 |
|     |     |        |       |               |
# skill
1. 字符串可通过nextline输入，包括空格，再通过toCharArray转换
2. 单词匹配和字符串匹配不同，单词匹配可通过切除空格进行存储
3. 某些时候可以不模拟（使用数组），而是直接从本质入手，来节省内存
4. java有更多封装api
5. 如果for==循环==高度重合，可考虑合并操作
6. `通过in.nextline();消耗掉换行符`
7. 位运算除2(>>)
8. `BufferedReader用于输入输出`
9. 字符串和整形之间转换使用Integer.parseInt toString
10. 通过Integer.parseInt将BufferedReader输入的字符串转为int
11. 

# 排序
快速和归并都是分治，归并是二等分，快速是选取pivot
 都使用了双指针
 
| 快速 | 归并 |
| --- | --- |
| 先操作，再递归 | 先递归，再操作 |
# 字符串
Arrays.sort/ toString用于分类和打印
>一般操作流
>String s;
>s=in.next();
>char[]arr=s.toCharArray();或String[]arrs=s.split("a");

比较使用equals(IgnoreCase)

# 递归

# 回溯
回溯是搜索方式



# 贪心
exp：miniRoad,miniTree, Huffman
糖果问题
自顶向下



# 动态规划
硬币问题：0-1背包
自底向上，本质是==穷举法==
~~区间和概率~~
## 背包

## 打家劫舍
## 股票
## 子序列

#  图
