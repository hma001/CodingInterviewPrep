# Coding Interview Revision Sheet (Neetcode 150 Focus)

## 1. Hash Tables  
**When to use:** Fast lookups (O(1)), counting  

- **Frequency maps / Counters**  
  - Trick: `hashmap[val] = hashmap.get(val, 0) + 1` (or `defaultdict(type)`)  
  - Common in: Anagrams, majority element, subarray sums  

- **Checking complements (2-sum pattern)**  
  - Trick: While iterating, check `target - num` in hashmap **before** inserting `num`  

- **Sets for uniqueness / cycle detection**  
  - Trick: Use a set to track seen elements (e.g., Linked List cycle, Happy Number)  

- **Prefix sums with hashmap**  
  - Trick: Store `{prefix_sum: earliest_index}` to find subarrays  

---

## 2. Two Pointers  
**When to use:** Sorted arrays, finding pairs/windows  

- **Opposite ends → meet in middle**  
  - Trick: Start `l=0, r=n-1`, move depending on condition (`sum < target → l++`)  

- **Skipping duplicates**  
  - Trick: While solving sorted problems, move pointer past duplicates to avoid repeats  

---

## 3. Sliding Window  
**When to use:** Subarrays/substrings, "longest/shortest/maximum/minimum window"  

- **Fixed window size**  
  - Trick: Keep a running sum/counter, update when window slides  

- **Variable window (expand + shrink)**  
  - Trick: Expand right pointer until invalid → shrink left until valid  

- **Hashmap + window**  
  - Trick: Track counts inside window; when constraint breaks, shrink from left  

- **Classic problems:** Longest substring without repeats, min window substring  

---

## 4. Stack  
**When to use:** Last-in-first-out, matching pairs, monotonic patterns  

- **Valid parentheses**  
  - Trick: Push opening brackets, check matching closing bracket  

- **Monotonic stack**  
  - Trick: Maintain increasing/decreasing stack for next greater/smaller element  

- **Evaluate expressions**  
  - Trick: Push numbers/operators, pop when operation resolves (RPN, calculator)  

- **Stack with index**  
  - Trick: Store `(value, index)` to calculate ranges (histogram, daily temperatures)  
