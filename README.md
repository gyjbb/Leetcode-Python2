# Leetcode-Python2
## 代码随想录算法训练营第二天|977.有序数组的平方、209.长度最小的子数组 、59.螺旋矩阵II 、总结 
May 10, 2023 

The second day and will finish learning Array.

## 977. Squares of a Sorted Array
[Leetcode link](https://leetcode.com/problems/squares-of-a-sorted-array/) \
[Video link](https://www.bilibili.com/video/BV1QB4y1D7ep/?spm_id_from=333.788&vd_source=63f26efad0d35bcbb0de794512ac21f3) \
[Reading link](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0977.%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9.md)\
Can use **double pointers** to  solve the problem. A left one and a right one, the one with bigger square will be returned to the last item of new result first.\
res = [float('inf')] * len(nums) # This is a good way to define a list with desired length to store the final result. \
![image](


