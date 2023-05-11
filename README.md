# Leetcode-Python2
## 代码随想录算法训练营第二天|977.有序数组的平方、209.长度最小的子数组 、59.螺旋矩阵II 、总结 
May 10, 2023 

The second day and will finish learning Array.

## 977. Squares of a Sorted Array
[Leetcode link](https://leetcode.com/problems/squares-of-a-sorted-array/) \
[Video link](https://www.bilibili.com/video/BV1QB4y1D7ep/?spm_id_from=333.788&vd_source=63f26efad0d35bcbb0de794512ac21f3) \
[Reading link](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0977.%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9.md)\
Can use **double pointers** to  solve the problem. A left one and a right one, the one with bigger square will be returned to the last item of new result first.\
res = [float('inf')] * len(nums) # This is a good way to define a list with desired length to store the final result. 

<img src="https://github.com/gyjbb/Leetcode-Python2/blob/main/Screen%20Shot%202023-05-10%20at%203.35.08%20PM.png" width="600" height="400">

## 209. Minimum Size Subarray Sum
[Leetcode link](https://leetcode.com/problems/minimum-size-subarray-sum/) \
[Video link](https://www.bilibili.com/video/BV1tZ4y1q7XE) \
[Reading link](https://github.com/youngyangyang04/leetcode-master/blob/master/problems/0209.%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84.md) \
This is about using **sliding window** to solve question. When all items before the end pointer euqal to or larger than the target, then adjusting the start pointer to narrow the window. record the minimum lenth. Then move to next end point.

<img src="https://github.com/gyjbb/Leetcode-Python2/blob/main/Screen%20Shot%202023-05-10%20at%204.32.31%20PM.png" width="700" height="400">

#### 907.
#### 76.


## 59. Spiral Matrix II
[Video link](https://www.bilibili.com/video/BV1SL4y1N7mV/?spm_id_from=333.788&vd_source=63f26efad0d35bcbb0de794512ac21f3) \
Follow the [ , ) rule, then define the start x and start y, which will change every time in the loop.\
Also, define an offset, which will decrease by 1 in every loop. \
And use count to record the number increase.\
(startx, starty)  (i,j)\
After each full loop, the (startx, starty) will add 1, and offset will add 1.

<img src="https://github.com/gyjbb/Leetcode-Python2/blob/main/Screen%20Shot%202023-05-10%20at%205.38.52%20PM.png" width="700" height="600">



#### 54. 







