# algorithm

## 2020.06.02

- 给定一个整数数组 nums 和一个目标值 target，请你在该数组中找出和为目标值的那 两个 整数，并返回他们的数组下标。

```
   var twoSum = function(nums, target) {
       for (let i = 0; i < nums.length; i++) {
         let index = nums.indexOf(target - nums[i]);
         if (index != -1 && index != i) {
               return [i,index];
         }
       }
   };
```

| 通过时间 | 时间消耗 | 内存消耗 |
| -------- | -------- | -------- |
| 10min    | 304ms    | 33.6M    |
***
# 2020.06.07

- 给定一个字符串，请你找出其中不含有重复字符的 **最长子串** 的长度。

```
示例 1:

输入: "abcabcbb"
输出: 3
解释: 因为无重复字符的最长子串是 "abc"，所以其长度为 3。
示例 2:

输入: "bbbbb"
输出: 1
解释: 因为无重复字符的最长子串是 "b"，所以其长度为 1。
示例 3:

输入: "pwwkew"
输出: 3
```

```
解释: 因为无重复字符的最长子串是 "wke"，所以其长度为 3。
     请注意，你的答案必须是 子串 的长度，"pwke" 是一个子序列，不是子串。
```
```js
```
