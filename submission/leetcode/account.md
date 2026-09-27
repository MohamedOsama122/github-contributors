# LeetCode Profile & Submission

- **Profile URL**: [https://leetcode.com/u/Mohamed_222/](https://leetcode.com/u/Mohamed_222/)
- **Username**: `@Mohamed_222`
- **Problem**: [LeetCode #344 - Reverse String](https://leetcode.com/problems/reverse-string/)
- **Submission Link**: [Submission #2140224892](https://leetcode.com/problems/reverse-string/submissions/2140224892/)

## Solution Code (C#)

```csharp
public class Solution {
    public void ReverseString(char[] s) {
        int left = 0, right = s.Length - 1;
        while (left < right) {
            char temp = s[left];
            s[left] = s[right];
            s[right] = temp;
            left++;
            right--;
        }
    }
}
```

## Complexity
- **Time Complexity**: O(n)
- **Space Complexity**: O(1) auxiliary space
