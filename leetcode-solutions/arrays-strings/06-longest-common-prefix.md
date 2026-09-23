## Problem: Longest Common Prefix (Easy)

**Link:** https://leetcode.com/problems/longest-common-prefix/description/

### Approach
I compared the characters of the strings from the beginning. I continued while all strings had the same character at the current position.

### Complexity
- Time: O(n × m)
- Space: O(1)

### Notes
If the strings have no common starting characters, the answer is an empty string. I also considered strings with different lengths.
