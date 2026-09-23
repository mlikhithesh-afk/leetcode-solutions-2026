## Problem: Best Time to Buy and Sell Stock (Easy)

**Link:** https://leetcode.com/problems/valid-anagram/description/

### Approach
I kept track of the lowest price seen so far while going through the array. For every price, I calculated the possible profit and kept the maximum profit.

### Complexity
- Time: O(n)
- Space: O(1)

### Notes
The stock must be bought before it is sold. If no profit is possible, the answer is 0.
