# Editorial: Two Sum Problem

# Two Sum Problem Editorial

## Problem Understanding

The Two Sum problem asks us to find two numbers in an array that add up to a specific target.

## Approach 1: Brute Force

The naive approach would be to check all pairs:

``````

**Time Complexity:** O(n²)
**Space Complexity:** O(1)

## Approach 2: Hash Map (Optimal)

We can solve this in O(n) time using a hash map:

``````

**Time Complexity:** O(n)
**Space Complexity:** O(n)

## Key Insights

1. Instead of checking all pairs, we can look for the complement
2. Hash map allows O(1) lookup time
3. We only need to traverse the array once

## Related Problems

- Three Sum
- Four Sum
- Two Sum II - Input array is sorted

## Media Assets
No media assets in this editorial.

---
*Last updated: 2025-07-31T15:30:12.931Z*  
*Author: John D*  
*Problem ID: 688b7ca8791eccad75ae6bb1*  
*Media assets synced: 0*
