# Visual DSA Roadmap

**Coding-interview algorithms you can watch.** Every lesson below is a 3-minute interactive page on [bytepatterns.com](https://bytepatterns.com?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap): a step-by-step animation you control, under 150 words of explanation, one real-world example, one exercise, and a three-question quiz. No wall of text.

This repository is the map. It is regenerated from the site's content, so the numbers and links are always current.

| | |
|---|---|
| Lessons | **218** across **29** modules (~19 hours) |
| Practice problems | **100** (26 easy · 59 medium · 15 hard) |
| Cost | Free. No account needed to read a lesson. |
| Machine-readable | [`roadmap.json`](roadmap.json) — every lesson and problem with its URL |

## How to use this map

1. Go phase by phase. Each phase is ordered so the next module only needs what came before it.
2. Inside a module, do the lessons in order — each animation builds on the previous one's picture.
3. After a module, do its practice problems. Hints unlock one at a time; the solution stays behind a gate until you ask for it.
4. Coming back before an interview? The one-liners below are the whole course in one screen.

## Contents

- [Foundations](#foundations)
  - [Big-O](#big-o)
  - [Arrays](#arrays)
  - [Strings](#strings)
  - [Searching](#searching)
  - [Sorting](#sorting)
- [Data Structures](#structures)
  - [Linked Lists](#linked-lists)
  - [Stacks & Queues](#stacks-queues)
  - [Hash Tables](#hash-tables)
  - [Trees & BST](#trees)
  - [Tries](#tries)
  - [Heaps](#heaps)
  - [Two Heaps & K-Way Merge](#two-heaps-k-way)
  - [Graphs](#graphs)
  - [Matrix & Grid](#matrix-grid)
  - [Union-Find](#union-find)
- [Algorithms](#algorithms)
  - [Recursion](#recursion)
  - [Backtracking](#backtracking)
  - [Greedy](#greedy)
  - [Intervals](#intervals)
  - [Bit Manipulation](#bit-manipulation)
  - [Math & Number Theory](#math-number-theory)
  - [Dynamic Programming](#dynamic-programming)
- [Systems](#systems)
  - [System Design](#system-design)
  - [System Design Cases](#system-design-cases)
  - [Concurrency](#concurrency)
  - [SQL](#sql)
- [The Rest of the Loop](#interview)
  - [Low-Level Design](#lld)
  - [Behavioral](#behavioral)
- [AI & ML](#ai)
  - [AI & ML](#ai-ml)
- [Practice problems](#practice-problems)

## Foundations

<a id="foundations"></a>

_Cost, then the one structure everything else is built on. Nothing here is optional._

### Big-O

<a id="big-o"></a>

[![Big-O](assets/modules/big-o.png)](https://bytepatterns.com/learn/big-o?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Read growth curves at a glance instead of memorising a table._ · 5 lessons · [open module](https://bytepatterns.com/learn/big-o?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Is Big-O?](https://bytepatterns.com/learn/big-o/what-is-big-o?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Stop timing code. Start predicting how it scales. | 4 |
| 2 | [O(1) and O(n)](https://bytepatterns.com/learn/big-o/o1-and-on?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One step, or every step? That's the whole difference. | 4 |
| 3 | [O(n²) and Nested Loops](https://bytepatterns.com/learn/big-o/on2-and-nested-loops?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every pair costs you. Nested loops explode fast. | 5 |
| 4 | [O(log n) and Halving](https://bytepatterns.com/learn/big-o/ologn-halving?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Throw away half the problem, every single step. | 4 |
| 5 | [Comparing Complexities](https://bytepatterns.com/learn/big-o/comparing-complexities?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | O(n log n) beats O(n²) long before you notice. | 5 |

### Arrays

<a id="arrays"></a>

[![Arrays](assets/modules/arrays.png)](https://bytepatterns.com/learn/arrays?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Pointers, windows and in-place tricks, drawn out step by step._ · 8 lessons · [open module](https://bytepatterns.com/learn/arrays?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Array Basics](https://bytepatterns.com/learn/arrays/array-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One block of memory, instant access to any slot. | 4 |
| 2 | [Two Pointers](https://bytepatterns.com/learn/arrays/two-pointers?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two indexes closing in beat one loop nesting another. | 5 |
| 3 | [Sliding Window](https://bytepatterns.com/learn/arrays/sliding-window?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Reuse the last answer instead of recomputing it. | 5 |
| 4 | [Prefix Sums](https://bytepatterns.com/learn/arrays/prefix-sums?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Pay once up front, answer range queries instantly. | 5 |
| 5 | [In-Place Reversal](https://bytepatterns.com/learn/arrays/in-place-reversal?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Flip an array with one temp variable, not a copy. | 4 |
| 6 | [Move Zeroes](https://bytepatterns.com/learn/arrays/move-zeroes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Push the junk to the back without losing the order. | 5 |
| 7 | [Container With Most Water](https://bytepatterns.com/learn/arrays/container-with-most-water?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The shorter wall decides. So move the shorter wall. | 6 |
| 8 | [Kadane's Algorithm](https://bytepatterns.com/learn/arrays/kadanes-algorithm?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Drop the past the moment it starts costing you. | 6 |

Practice: [Single Stock Trade](https://bytepatterns.com/practice/arrays/single-stock-trade?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Drop Sorted Duplicates](https://bytepatterns.com/practice/arrays/drop-sorted-duplicates?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Product Of Others](https://bytepatterns.com/practice/arrays/product-of-others?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Longest Distinct Run](https://bytepatterns.com/practice/arrays/longest-distinct-run?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Window Maximums](https://bytepatterns.com/practice/arrays/window-maximums?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Majority Value](https://bytepatterns.com/practice/arrays/majority-value-finder?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Rotate Right By K](https://bytepatterns.com/practice/arrays/rotate-right-by-k?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Spiral Grid Walk](https://bytepatterns.com/practice/arrays/spiral-grid-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Strings

<a id="strings"></a>

[![Strings](assets/modules/strings.png)](https://bytepatterns.com/learn/strings?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Characters in a row — palindromes, windows, and the hashing that finds a needle fast._ · 7 lessons · [open module](https://bytepatterns.com/learn/strings?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [String Basics](https://bytepatterns.com/learn/strings/string-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Strings never change — every edit builds a brand-new one. | 4 |
| 2 | [Valid Palindrome](https://bytepatterns.com/learn/strings/valid-palindrome?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two pointers walk inward and settle it in one pass. | 4 |
| 3 | [Reverse Words](https://bytepatterns.com/learn/strings/reverse-words?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Flip the word order without disturbing the letters. | 4 |
| 4 | [Longest Unique Substring](https://bytepatterns.com/learn/strings/longest-substring-without-repeats?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Grow a window, shrink it the moment a letter repeats. | 5 |
| 5 | [Longest Palindromic Substring](https://bytepatterns.com/learn/strings/longest-palindromic-substring?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Stand on every centre and push outwards. | 5 |
| 6 | [Rabin-Karp Rolling Hash](https://bytepatterns.com/learn/strings/rabin-karp-rolling-hash?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Slide a number across the text instead of re-reading it. | 5 |
| 7 | [String Matching Intuition](https://bytepatterns.com/learn/strings/string-matching-intuition?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A mismatch already tells you where to restart. | 5 |

Practice: [Longest Shared Prefix](https://bytepatterns.com/practice/strings/longest-shared-prefix?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [First Unique Character](https://bytepatterns.com/practice/strings/first-unique-character?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Run Length Compression](https://bytepatterns.com/practice/strings/run-length-compression?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Multiply Digit Strings](https://bytepatterns.com/practice/strings/multiply-digit-strings?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Minimum Window Cover](https://bytepatterns.com/practice/strings/minimum-window-cover?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Group Anagrams Together](https://bytepatterns.com/practice/strings/group-anagrams-together?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Repeated DNA Sequences](https://bytepatterns.com/practice/strings/repeated-dna-sequences?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Searching

<a id="searching"></a>

[![Searching](assets/modules/searching.png)](https://bytepatterns.com/learn/searching?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Watch a search space collapse until only the answer is left._ · 5 lessons · [open module](https://bytepatterns.com/learn/searching?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Linear Search](https://bytepatterns.com/learn/searching/linear-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The simple one that always works. Often that's enough. | 3 |
| 2 | [Binary Search](https://bytepatterns.com/learn/searching/binary-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A million records, twenty guesses. Sorted data only. | 5 |
| 3 | [Binary Search Variants](https://bytepatterns.com/learn/searching/binary-search-variants?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Don't just find it. Find the first one that qualifies. | 6 |
| 4 | [Search in Rotated Array](https://bytepatterns.com/learn/searching/search-in-rotated-array?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Half of it is still sorted. Find that half, use it. | 6 |
| 5 | [Binary Search on Answer](https://bytepatterns.com/learn/searching/binary-search-on-answer?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | No sorted array? Binary search the answer range. | 6 |

Practice: [Integer Square Root](https://bytepatterns.com/practice/searching/integer-square-root?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Peak In Bumpy List](https://bytepatterns.com/practice/searching/peak-in-bumpy-list?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Median Of Two Sorted Lists](https://bytepatterns.com/practice/searching/median-of-two-sorted-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [First And Last Occurrence](https://bytepatterns.com/practice/searching/first-and-last-occurrence?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Minimum Daily Capacity](https://bytepatterns.com/practice/searching/minimum-daily-capacity?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Sorting

<a id="sorting"></a>

[![Sorting](assets/modules/sorting.png)](https://bytepatterns.com/learn/sorting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_See why the clever sorts beat the obvious ones._ · 8 lessons · [open module](https://bytepatterns.com/learn/sorting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Sorting Basics](https://bytepatterns.com/learn/sorting/sorting-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Comparisons, swaps, stability: the vocabulary of order. | 4 |
| 2 | [Bubble Sort](https://bytepatterns.com/learn/sorting/bubble-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Swap neighbours until the big values float to the end. | 4 |
| 3 | [Selection Sort](https://bytepatterns.com/learn/sorting/selection-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Find the smallest, put it in front, then do it again. | 4 |
| 4 | [Insertion Sort](https://bytepatterns.com/learn/sorting/insertion-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Build a sorted run, slide each newcomer into place. | 5 |
| 5 | [Merge Sort](https://bytepatterns.com/learn/sorting/merge-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Split until trivial, then merge your way back up. | 6 |
| 6 | [Quick Sort](https://bytepatterns.com/learn/sorting/quick-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Pick a pivot, split around it, and never merge. | 6 |
| 7 | [Counting Sort](https://bytepatterns.com/learn/sorting/counting-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Skip comparisons entirely when the values are small. | 5 |
| 8 | [Which Sort When?](https://bytepatterns.com/learn/sorting/which-sort-when?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The right sort is the one that fits your data's shape. | 5 |

Practice: [Out Of Place Count](https://bytepatterns.com/practice/sorting/out-of-place-count?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Three Way Flag Sort](https://bytepatterns.com/practice/sorting/three-way-flag-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Largest Number Arrangement](https://bytepatterns.com/practice/sorting/largest-number-arrangement?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [H Index From Citations](https://bytepatterns.com/practice/sorting/h-index-citations?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Maximum Gap Buckets](https://bytepatterns.com/practice/sorting/maximum-gap-buckets?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

## Data Structures

<a id="structures"></a>

_Ten shapes for holding data, and the trade each one makes to be fast at something._

### Linked Lists

<a id="linked-lists"></a>

[![Linked Lists](assets/modules/linked-lists.png)](https://bytepatterns.com/learn/linked-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Follow the pointers — and learn every trick they hide._ · 6 lessons · [open module](https://bytepatterns.com/learn/linked-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Singly Linked List Basics](https://bytepatterns.com/learn/linked-lists/singly-linked-list-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Each item carries the address of the next one. | 4 |
| 2 | [Traversal and Search](https://bytepatterns.com/learn/linked-lists/traversal-and-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One node at a time is the only way through. | 4 |
| 3 | [Insert and Delete](https://bytepatterns.com/learn/linked-lists/insert-and-delete?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Rewire two links, and nothing else has to move. | 5 |
| 4 | [Reverse a Linked List](https://bytepatterns.com/learn/linked-lists/reverse-linked-list?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Flip every arrow backwards using three pointers. | 5 |
| 5 | [Fast and Slow Pointers](https://bytepatterns.com/learn/linked-lists/fast-and-slow-pointers?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One hop versus two finds the middle in one pass. | 5 |
| 6 | [Detect a Cycle](https://bytepatterns.com/learn/linked-lists/detect-cycle?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | If the list loops, the fast pointer laps the slow one. | 5 |

Practice: [Merge Sorted Chains](https://bytepatterns.com/practice/linked-lists/merge-sorted-chains?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Drop Nth From End](https://bytepatterns.com/practice/linked-lists/drop-nth-from-end?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Weave List Halves](https://bytepatterns.com/practice/linked-lists/weave-list-halves?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Remove Value Nodes](https://bytepatterns.com/practice/linked-lists/remove-value-nodes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Add Two Digit Chains](https://bytepatterns.com/practice/linked-lists/add-two-digit-chains?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Partition Around Value](https://bytepatterns.com/practice/linked-lists/partition-around-value?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Stacks & Queues

<a id="stacks-queues"></a>

[![Stacks & Queues](assets/modules/stacks-queues.png)](https://bytepatterns.com/learn/stacks-queues?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Two humble rules, LIFO and FIFO, doing surprisingly heavy lifting._ · 5 lessons · [open module](https://bytepatterns.com/learn/stacks-queues?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Stack Basics](https://bytepatterns.com/learn/stacks-queues/stack-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Last one in is the first one out. | 4 |
| 2 | [Valid Parentheses](https://bytepatterns.com/learn/stacks-queues/valid-parentheses?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A closing bracket must answer the newest opening one. | 5 |
| 3 | [Queue Basics](https://bytepatterns.com/learn/stacks-queues/queue-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | First one in is the first one out. | 4 |
| 4 | [Queue From Two Stacks](https://bytepatterns.com/learn/stacks-queues/queue-with-two-stacks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Reverse a reversal and LIFO turns into FIFO. | 5 |
| 5 | [Monotonic Stack](https://bytepatterns.com/learn/stacks-queues/monotonic-stack?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Keep the stack ordered and every item waits only once. | 6 |

Practice: [Constant Time Min Stack](https://bytepatterns.com/practice/stacks-queues/constant-time-min-stack?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Days Until Warmer](https://bytepatterns.com/practice/stacks-queues/days-until-warmer?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Collapse Adjacent Pairs](https://bytepatterns.com/practice/stacks-queues/collapse-adjacent-pairs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Decode Nested Repeats](https://bytepatterns.com/practice/stacks-queues/decode-nested-repeats?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Largest Bar Rectangle](https://bytepatterns.com/practice/stacks-queues/largest-bar-rectangle?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

### Hash Tables

<a id="hash-tables"></a>

[![Hash Tables](assets/modules/hash-tables.png)](https://bytepatterns.com/learn/hash-tables?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Trade a bit of memory for answers in constant time._ · 5 lessons · [open module](https://bytepatterns.com/learn/hash-tables?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Hash Table Basics](https://bytepatterns.com/learn/hash-tables/hash-table-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Turn a key into an address and skip the search. | 4 |
| 2 | [Two Sum](https://bytepatterns.com/learn/hash-tables/two-sum?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Remember what you have seen and the pair finds itself. | 5 |
| 3 | [Frequency Counting](https://bytepatterns.com/learn/hash-tables/frequency-counting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One pass, one counter per distinct value. | 4 |
| 4 | [Group Anagrams](https://bytepatterns.com/learn/hash-tables/group-anagrams?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Give every item a canonical key, then bucket by it. | 5 |
| 5 | [When Hashing Fails](https://bytepatterns.com/learn/hash-tables/when-hashing-fails?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | O(1) is an average, not a promise. | 5 |

Practice: [Repeated Value Check](https://bytepatterns.com/practice/hash-tables/repeated-value-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Subarrays Summing To K](https://bytepatterns.com/practice/hash-tables/subarrays-summing-to-k?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Longest Consecutive Run](https://bytepatterns.com/practice/hash-tables/longest-consecutive-run?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Shared Values Of Two Lists](https://bytepatterns.com/practice/hash-tables/shared-values-of-two-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Consistent Renaming Check](https://bytepatterns.com/practice/hash-tables/consistent-renaming-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Four List Zero Tuples](https://bytepatterns.com/practice/hash-tables/four-list-zero-tuples?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Trees & BST

<a id="trees"></a>

[![Trees & BST](assets/modules/trees.png)](https://bytepatterns.com/learn/trees?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Hierarchies, ordered searches, and the paths between nodes._ · 8 lessons · [open module](https://bytepatterns.com/learn/trees?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Tree Basics](https://bytepatterns.com/learn/trees/tree-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One root, many branches, and no way back up. | 4 |
| 2 | [Binary Trees](https://bytepatterns.com/learn/trees/binary-trees?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | At most two children: one left, one right, never swapped. | 4 |
| 3 | [Tree Traversals](https://bytepatterns.com/learn/trees/tree-traversals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Same nodes, same recursion, three different reading orders. | 5 |
| 4 | [BST Basics](https://bytepatterns.com/learn/trees/bst-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Smaller values left, larger values right, all the way down. | 5 |
| 5 | [BST Insert and Search](https://bytepatterns.com/learn/trees/bst-insert-and-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One comparison per level throws away half the tree. | 5 |
| 6 | [Validate a BST](https://bytepatterns.com/learn/trees/validate-bst?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Checking the parent is not enough; carry a range down. | 6 |
| 7 | [Tree Depth and Balance](https://bytepatterns.com/learn/trees/tree-depth-and-balance?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Height decides speed, and balance decides height. | 5 |
| 8 | [Lowest Common Ancestor](https://bytepatterns.com/learn/trees/lowest-common-ancestor?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Walk down from the root until the two targets part ways. | 6 |

Practice: [Deepest Level Count](https://bytepatterns.com/practice/trees/deepest-level-count?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Zigzag Level Walk](https://bytepatterns.com/practice/trees/zigzag-level-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Right Edge View](https://bytepatterns.com/practice/trees/right-edge-view?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Mirror Symmetry Check](https://bytepatterns.com/practice/trees/mirror-symmetry-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Root To Leaf Target Sum](https://bytepatterns.com/practice/trees/root-to-leaf-target-sum?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Widest Node To Node Path](https://bytepatterns.com/practice/trees/widest-node-to-node-path?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Rebuild From Two Walks](https://bytepatterns.com/practice/trees/rebuild-from-two-walks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

### Tries

<a id="tries"></a>

[![Tries](assets/modules/tries.png)](https://bytepatterns.com/learn/tries?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_A tree of prefixes: autocomplete, word search and spell-check in one shape._ · 4 lessons · [open module](https://bytepatterns.com/learn/tries?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Trie Basics](https://bytepatterns.com/learn/tries/trie-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Store words by their letters so shared prefixes are stored once. | 5 |
| 2 | [Prefix Search](https://bytepatterns.com/learn/tries/prefix-autocomplete?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Walk to the prefix once, then everything below it is the answer. | 5 |
| 3 | [Word Search With a Trie](https://bytepatterns.com/learn/tries/word-search-trie?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One walk over the grid, pruned the moment the path stops being a prefix. | 6 |
| 4 | [Trie vs Hash Set](https://bytepatterns.com/learn/tries/trie-vs-hash-set?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A set answers 'is this word here'. A trie answers 'what starts with this'. | 4 |

Practice: [Wildcard Word Search](https://bytepatterns.com/practice/tries/wildcard-word-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Replace Words With Roots](https://bytepatterns.com/practice/tries/replace-words-with-roots?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Maximum XOR Pair](https://bytepatterns.com/practice/tries/maximum-xor-pair?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

### Heaps

<a id="heaps"></a>

[![Heaps](assets/modules/heaps.png)](https://bytepatterns.com/learn/heaps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Keep the most important thing on top — without sorting the rest._ · 4 lessons · [open module](https://bytepatterns.com/learn/heaps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Heap Basics](https://bytepatterns.com/learn/heaps/heap-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Not sorted — just guaranteed to know its own winner. | 5 |
| 2 | [Heapify and Sift](https://bytepatterns.com/learn/heaps/heapify-and-sift?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One wrong value walks a single path back into place. | 6 |
| 3 | [Priority Queue](https://bytepatterns.com/learn/heaps/priority-queue?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Serve by urgency, not by who shouted first. | 5 |
| 4 | [Top K Elements](https://bytepatterns.com/learn/heaps/top-k-elements?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hold k winners and let the weakest one guard the door. | 6 |

Practice: [Kth Largest Value](https://bytepatterns.com/practice/heaps/kth-largest-value?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Smash Heaviest Stones](https://bytepatterns.com/practice/heaps/smash-heaviest-stones?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Closest Points To Origin](https://bytepatterns.com/practice/heaps/closest-points-to-origin?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Running Median Stream](https://bytepatterns.com/practice/heaps/running-median-stream?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Task Scheduler Cooldown](https://bytepatterns.com/practice/heaps/task-scheduler-cooldown?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Reorganize String Gaps](https://bytepatterns.com/practice/heaps/reorganize-string-gaps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Two Heaps & K-Way Merge

<a id="two-heaps-k-way"></a>

[![Two Heaps & K-Way Merge](assets/modules/two-heaps-k-way.png)](https://bytepatterns.com/learn/two-heaps-k-way?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Two heaps that lean on each other, and one that merges k sorted streams._ · 4 lessons · [open module](https://bytepatterns.com/learn/two-heaps-k-way?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Two Heaps: Running Median](https://bytepatterns.com/learn/two-heaps-k-way/two-heaps-running-median?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two heaps face each other, and the middle sits between their roots. | 6 |
| 2 | [K-Way Merge](https://bytepatterns.com/learn/two-heaps-k-way/k-way-merge?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One heap of k heads turns k sorted lists into one. | 6 |
| 3 | [Top K in a Stream](https://bytepatterns.com/learn/two-heaps-k-way/top-k-frequent-stream?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Count once, then let a k-sized heap keep only the winners. | 6 |
| 4 | [Sliding Window Median](https://bytepatterns.com/learn/two-heaps-k-way/sliding-window-median?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | You cannot dig a value out of a heap — so mark it dead instead. | 7 |

Practice: [Kth Smallest In Matrix](https://bytepatterns.com/practice/two-heaps-k-way/kth-smallest-in-sorted-matrix?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Smallest Range K Lists](https://bytepatterns.com/practice/two-heaps-k-way/smallest-range-k-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Capital Project Picks](https://bytepatterns.com/practice/two-heaps-k-way/capital-project-picks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

### Graphs

<a id="graphs"></a>

[![Graphs](assets/modules/graphs.png)](https://bytepatterns.com/learn/graphs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Nodes, edges, and the searches that ripple across them._ · 8 lessons · [open module](https://bytepatterns.com/learn/graphs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Graph Basics](https://bytepatterns.com/learn/graphs/graph-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Things, plus the connections between them. | 5 |
| 2 | [List vs Matrix](https://bytepatterns.com/learn/graphs/adjacency-representations?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Store the edges you have, or a cell for every pair you don't. | 5 |
| 3 | [Breadth-First Search](https://bytepatterns.com/learn/graphs/breadth-first-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Sweep outward one ring at a time, using a queue. | 6 |
| 4 | [Depth-First Search](https://bytepatterns.com/learn/graphs/depth-first-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Commit to one branch until it dead-ends, then back up. | 5 |
| 5 | [Connected Components](https://bytepatterns.com/learn/graphs/connected-components?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Count the islands by starting a fresh sweep on each one. | 5 |
| 6 | [Shortest Path, Unweighted](https://bytepatterns.com/learn/graphs/shortest-path-unweighted?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | BFS already found it — store parents to read it back. | 6 |
| 7 | [Dijkstra's Algorithm](https://bytepatterns.com/learn/graphs/dijkstra-intro?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | When edges cost different amounts, always settle the nearest first. | 6 |
| 8 | [Topological Sort](https://bytepatterns.com/learn/graphs/topological-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Order the steps so nothing runs before what it depends on. | 6 |

Practice: [Count Island Blobs](https://bytepatterns.com/practice/graphs/count-island-blobs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Course Order Feasibility](https://bytepatterns.com/practice/graphs/course-order-feasibility?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Word Ladder Steps](https://bytepatterns.com/practice/graphs/word-ladder-steps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Trusted Town Judge](https://bytepatterns.com/practice/graphs/trusted-town-judge?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Deep Copy A Graph](https://bytepatterns.com/practice/graphs/deep-copy-a-graph?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Spreading Rot Minutes](https://bytepatterns.com/practice/graphs/spreading-rot-minutes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Two Colour Split Check](https://bytepatterns.com/practice/graphs/two-colour-split-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Matrix & Grid

<a id="matrix-grid"></a>

[![Matrix & Grid](assets/modules/matrix-grid.png)](https://bytepatterns.com/learn/matrix-grid?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Rows, columns and neighbours — the grid problems interviews keep drawing._ · 5 lessons · [open module](https://bytepatterns.com/learn/matrix-grid?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Grid Traversal](https://bytepatterns.com/learn/matrix-grid/grid-traversal-neighbours?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Row first, column second, and always check the edge. | 4 |
| 2 | [Spiral Order](https://bytepatterns.com/learn/matrix-grid/grid-spiral-order?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Four walls that close in after every pass. | 5 |
| 3 | [Rotate In Place](https://bytepatterns.com/learn/matrix-grid/grid-rotate-in-place?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Mirror the diagonal, then flip each row. | 5 |
| 4 | [Number of Islands](https://bytepatterns.com/learn/matrix-grid/grid-island-count?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Count a blob once, then erase it so it cannot count twice. | 5 |
| 5 | [Flood Fill](https://bytepatterns.com/learn/matrix-grid/grid-flood-fill?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Spread while the colour matches, stop the moment it does not. | 4 |

Practice: [Perimeter Of An Island](https://bytepatterns.com/practice/matrix-grid/island-perimeter-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Zero Out Rows And Columns](https://bytepatterns.com/practice/matrix-grid/zero-out-rows-and-columns?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Search A Sorted Grid](https://bytepatterns.com/practice/matrix-grid/staircase-grid-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Union-Find

<a id="union-find"></a>

[![Union-Find](assets/modules/union-find.png)](https://bytepatterns.com/learn/union-find?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Merge groups in near-constant time, then ask who belongs together._ · 4 lessons · [open module](https://bytepatterns.com/learn/union-find?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Disjoint Sets Basics](https://bytepatterns.com/learn/union-find/disjoint-sets-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every group is named by one root, and find walks up to it. | 5 |
| 2 | [Path Compression](https://bytepatterns.com/learn/union-find/path-compression?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | You already walked to the root — leave everyone pointing straight at it. | 5 |
| 3 | [Union by Rank or Size](https://bytepatterns.com/learn/union-find/union-by-size?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hang the smaller tree under the bigger one and depth barely grows. | 5 |
| 4 | [Components & Cycles](https://bytepatterns.com/learn/union-find/dsu-components-and-cycles?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Start the counter at n and drop it on every union that actually merges. | 5 |

Practice: [Count Provinces](https://bytepatterns.com/practice/union-find/count-provinces?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Redundant Connection](https://bytepatterns.com/practice/union-find/redundant-connection?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Accounts Merge By Email](https://bytepatterns.com/practice/union-find/accounts-merge-emails?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

## Algorithms

<a id="algorithms"></a>

_Recursion, backtracking and greedy choices, then recursion with a memo — plus the sweep-line, bit and number tricks that are pure technique._

### Recursion

<a id="recursion"></a>

[![Recursion](assets/modules/recursion.png)](https://bytepatterns.com/learn/recursion?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Watch the call stack grow, shrink, and finally make sense._ · 5 lessons · [open module](https://bytepatterns.com/learn/recursion?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Recursion Basics](https://bytepatterns.com/learn/recursion/recursion-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A function that solves a smaller copy of itself. | 5 |
| 2 | [The Call Stack](https://bytepatterns.com/learn/recursion/call-stack-visualized?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every pending call waits its turn on a stack of frames. | 5 |
| 3 | [Factorial and Fibonacci](https://bytepatterns.com/learn/recursion/factorial-and-fibonacci?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One call per step, or two calls that redo everything. | 6 |
| 4 | [Memoization](https://bytepatterns.com/learn/recursion/memoization-intro?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Write each answer down once, never solve it twice. | 5 |
| 5 | [Backtracking](https://bytepatterns.com/learn/recursion/backtracking-intro?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Choose, explore, then undo the choice and try the next. | 6 |

Practice: [Flatten a Nested List](https://bytepatterns.com/practice/recursion/flatten-nested-counts?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Disc Tower Moves](https://bytepatterns.com/practice/recursion/disc-tower-moves?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Fast Power](https://bytepatterns.com/practice/recursion/fast-power-of-a-number?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Backtracking

<a id="backtracking"></a>

[![Backtracking](assets/modules/backtracking.png)](https://bytepatterns.com/learn/backtracking?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Try a choice, go deeper, undo it — and prune the branches that cannot win._ · 5 lessons · [open module](https://bytepatterns.com/learn/backtracking?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [The Decision Tree](https://bytepatterns.com/learn/backtracking/backtracking-decision-tree?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Choose, explore, un-choose — one shared path walks the whole tree. | 5 |
| 2 | [Subsets](https://bytepatterns.com/learn/backtracking/subsets-include-exclude?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two branches per item: leave it out, or take it. | 5 |
| 3 | [Permutations](https://bytepatterns.com/learn/backtracking/permutations-used-set?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every unused value is a branch; the used set is the pruning. | 5 |
| 4 | [N-Queens](https://bytepatterns.com/learn/backtracking/n-queens-rows?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One queen per row, and a dead row sends you straight back up. | 6 |
| 5 | [Word Search & Pruning](https://bytepatterns.com/learn/backtracking/word-search-pruning?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Walk the grid, block the cell, and quit on the first wrong letter. | 6 |

Practice: [Phone Keypad Words](https://bytepatterns.com/practice/backtracking/phone-keypad-words?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Combinations That Sum](https://bytepatterns.com/practice/backtracking/combinations-summing-to-target?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Split Into Palindromes](https://bytepatterns.com/practice/backtracking/split-into-palindrome-pieces?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Greedy

<a id="greedy"></a>

[![Greedy](assets/modules/greedy.png)](https://bytepatterns.com/learn/greedy?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Take the best local move and see exactly when that is enough._ · 5 lessons · [open module](https://bytepatterns.com/learn/greedy?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Makes Greedy Work](https://bytepatterns.com/learn/greedy/greedy-when-it-works?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Take the best move now — but only when it can never block a better answer. | 5 |
| 2 | [Interval Scheduling](https://bytepatterns.com/learn/greedy/interval-scheduling-greedy?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Sort by finishing time and the room books itself. | 5 |
| 3 | [Jump Game](https://bytepatterns.com/learn/greedy/jump-game-reach?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Carry one number: the furthest index still in reach. | 5 |
| 4 | [Gas Station](https://bytepatterns.com/learn/greedy/gas-station-start?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One pass picks the start, because every failed prefix is proof. | 6 |
| 5 | [Huffman Intuition](https://bytepatterns.com/learn/greedy/huffman-intuition?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Merge the two rarest symbols, again and again, and the code writes itself. | 6 |

Practice: [Fewest Removals to Unclash](https://bytepatterns.com/practice/greedy/fewest-removals-to-unclash?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Fewest Hops to the End](https://bytepatterns.com/practice/greedy/fewest-hops-to-the-end?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Split String Into Blocks](https://bytepatterns.com/practice/greedy/split-string-into-blocks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Intervals

<a id="intervals"></a>

[![Intervals](assets/modules/intervals.png)](https://bytepatterns.com/learn/intervals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Sort by start, sweep once — merges, overlaps and meeting rooms fall out._ · 4 lessons · [open module](https://bytepatterns.com/learn/intervals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Interval Basics & Sorting](https://bytepatterns.com/learn/intervals/interval-basics-sorting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Sort by start and the pairwise question becomes a left-to-right scan. | 4 |
| 2 | [Merge Intervals](https://bytepatterns.com/learn/intervals/merge-intervals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hold one block open, stretch it while they touch, close it on a gap. | 5 |
| 3 | [Insert Interval](https://bytepatterns.com/learn/intervals/insert-interval?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The list is already sorted, so slot the new block in with three passes. | 5 |
| 4 | [Meeting Rooms](https://bytepatterns.com/learn/intervals/meeting-rooms?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Count how many run at once; the high-water mark is the room count. | 5 |

Practice: [Non Overlapping Removals](https://bytepatterns.com/practice/intervals/non-overlapping-removals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Employee Free Time](https://bytepatterns.com/practice/intervals/employee-free-time?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Car Pooling Capacity](https://bytepatterns.com/practice/intervals/car-pooling-capacity?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Bit Manipulation

<a id="bit-manipulation"></a>

[![Bit Manipulation](assets/modules/bit-manipulation.png)](https://bytepatterns.com/learn/bit-manipulation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Flip, mask and shift — the tricks that turn a loop into one instruction._ · 5 lessons · [open module](https://bytepatterns.com/learn/bit-manipulation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Binary and Bitwise Ops](https://bytepatterns.com/learn/bit-manipulation/binary-and-bitwise-ops?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every integer is a row of switches you can address. | 4 |
| 2 | [XOR Tricks](https://bytepatterns.com/learn/bit-manipulation/xor-single-number?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Pairs cancel out, and the loner is left standing. | 4 |
| 3 | [Counting Set Bits](https://bytepatterns.com/learn/bit-manipulation/counting-set-bits?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Clear the lowest 1 and count how often you can. | 4 |
| 4 | [Masks and Power of Two](https://bytepatterns.com/learn/bit-manipulation/masks-and-power-of-two?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One shifted bit is a key to any position you like. | 5 |
| 5 | [Bitmask as a Set](https://bytepatterns.com/learn/bit-manipulation/bitmask-as-a-set?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | An integer is a subset; counting to 2^n lists them all. | 5 |

Practice: [Reverse Bit Order](https://bytepatterns.com/practice/bit-manipulation/reverse-bit-order?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Single Value Among Triples](https://bytepatterns.com/practice/bit-manipulation/single-value-among-triples?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [The Missing Value](https://bytepatterns.com/practice/bit-manipulation/missing-value-in-range?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy)

### Math & Number Theory

<a id="math-number-theory"></a>

[![Math & Number Theory](assets/modules/math-number-theory.png)](https://bytepatterns.com/learn/math-number-theory?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Modular arithmetic, primes and fast powers, drawn so the shortcuts make sense._ · 5 lessons · [open module](https://bytepatterns.com/learn/math-number-theory?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Modular Arithmetic](https://bytepatterns.com/learn/math-number-theory/modular-arithmetic?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A remainder is a position on a clock, not a leftover. | 4 |
| 2 | [GCD and Euclid](https://bytepatterns.com/learn/math-number-theory/gcd-euclid?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Replace the pair with the leftover and it shrinks fast. | 4 |
| 3 | [Sieve of Eratosthenes](https://bytepatterns.com/learn/math-number-theory/sieve-of-eratosthenes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Cross out what the primes can reach; the rest are prime. | 5 |
| 4 | [Fast Exponentiation](https://bytepatterns.com/learn/math-number-theory/fast-exponentiation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Square your way up instead of multiplying n times. | 5 |
| 5 | [Permutations vs Combinations](https://bytepatterns.com/learn/math-number-theory/counting-permutations-combinations?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Divide by k! the moment order stops mattering. | 5 |

Practice: [Trailing Zeros Of A Factorial](https://bytepatterns.com/practice/math-number-theory/factorial-trailing-zeros?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Primes Below A Limit](https://bytepatterns.com/practice/math-number-theory/primes-below-limit?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Power Under A Modulus](https://bytepatterns.com/practice/math-number-theory/power-under-modulus?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium)

### Dynamic Programming

<a id="dynamic-programming"></a>

[![Dynamic Programming](assets/modules/dynamic-programming.png)](https://bytepatterns.com/learn/dynamic-programming?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Solve every subproblem once, then let the table do the work._ · 10 lessons · [open module](https://bytepatterns.com/learn/dynamic-programming?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Is Dynamic Programming?](https://bytepatterns.com/learn/dynamic-programming/what-is-dp?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Solve each overlapping subproblem once, then reuse the answer. | 5 |
| 2 | [Top-Down vs Bottom-Up](https://bytepatterns.com/learn/dynamic-programming/top-down-vs-bottom-up?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One recurrence, two directions: recurse and cache, or fill a table. | 5 |
| 3 | [Climbing Stairs](https://bytepatterns.com/learn/dynamic-programming/climbing-stairs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Ways to reach step n = ways to n-1 plus ways to n-2. | 4 |
| 4 | [House Robber](https://bytepatterns.com/learn/dynamic-programming/house-robber?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Take this one and skip its neighbour, or skip it and keep the best. | 5 |
| 5 | [Coin Change](https://bytepatterns.com/learn/dynamic-programming/coin-change?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Fewest pieces to hit a target, one amount at a time. | 6 |
| 6 | [Longest Common Subsequence](https://bytepatterns.com/learn/dynamic-programming/longest-common-subsequence?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Match the two ends, or drop a character from one side. | 6 |
| 7 | [0/1 Knapsack](https://bytepatterns.com/learn/dynamic-programming/knapsack-01?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Each item is all or nothing, so try both and keep the better. | 6 |
| 8 | [Edit Distance](https://bytepatterns.com/learn/dynamic-programming/edit-distance?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Insert, delete, or replace — count the cheapest route. | 6 |
| 9 | [Longest Increasing Subsequence](https://bytepatterns.com/learn/dynamic-programming/longest-increasing-subsequence?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every element asks which smaller one it can extend. | 6 |
| 10 | [DP on Grids](https://bytepatterns.com/learn/dynamic-programming/dp-on-grids?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Each cell's answer comes from the cells above and to its left. | 6 |

Practice: [Cheapest Stair Climb](https://bytepatterns.com/practice/dynamic-programming/cheapest-stair-climb?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Grid Paths With Blocks](https://bytepatterns.com/practice/dynamic-programming/grid-paths-with-blocks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Sentence Segmentation](https://bytepatterns.com/practice/dynamic-programming/sentence-segmentation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Trading With Cooldown](https://bytepatterns.com/practice/dynamic-programming/trading-with-cooldown?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard) · [Paint Houses Cheaply](https://bytepatterns.com/practice/dynamic-programming/paint-houses-cheaply?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (easy) · [Decode Digit Message](https://bytepatterns.com/practice/dynamic-programming/decode-digit-message?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Unique BST Shapes](https://bytepatterns.com/practice/dynamic-programming/unique-bst-shapes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (medium) · [Pop Balloons For Coins](https://bytepatterns.com/practice/dynamic-programming/pop-balloons-for-coins?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (hard)

## Systems

<a id="systems"></a>

_What happens once one machine is not enough — and once one thread is not either._

### System Design

<a id="system-design"></a>

[![System Design](assets/modules/system-design.png)](https://bytepatterns.com/learn/system-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Scale, cache, shard — and know what each choice costs you._ · 15 lessons · [open module](https://bytepatterns.com/learn/system-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Is System Design](https://bytepatterns.com/learn/system-design/what-is-system-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Choosing which constraint you refuse to break. | 5 |
| 2 | [Vertical vs Horizontal Scaling](https://bytepatterns.com/learn/system-design/vertical-vs-horizontal-scaling?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Buy a bigger machine, or buy more of them. | 5 |
| 3 | [Load Balancing](https://bytepatterns.com/learn/system-design/load-balancing?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One front door, many rooms behind it. | 5 |
| 4 | [Caching](https://bytepatterns.com/learn/system-design/caching-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Keep the answer near whoever keeps asking. | 5 |
| 5 | [Invalidation and Eviction](https://bytepatterns.com/learn/system-design/cache-invalidation-and-eviction?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Wrong answers age; small caches forget. | 6 |
| 6 | [Content Delivery Networks](https://bytepatterns.com/learn/system-design/cdn-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Distance is latency you cannot optimise away. | 5 |
| 7 | [Database Replication](https://bytepatterns.com/learn/system-design/database-replication?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One writer, many readers, a small delay. | 6 |
| 8 | [Database Sharding](https://bytepatterns.com/learn/system-design/database-sharding?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Split the data itself when one box is full. | 6 |
| 9 | [SQL vs NoSQL](https://bytepatterns.com/learn/system-design/sql-vs-nosql?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Fixed columns and joins, or flexible documents. | 6 |
| 10 | [Consistency and CAP](https://bytepatterns.com/learn/system-design/consistency-and-cap?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | When the network splits, you must pick a side. | 6 |
| 11 | [Message Queues](https://bytepatterns.com/learn/system-design/message-queues?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hand off the work instead of waiting for it. | 5 |
| 12 | [Rate Limiting](https://bytepatterns.com/learn/system-design/rate-limiting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Cap the flow before it caps your service. | 5 |
| 13 | [Designing a REST API](https://bytepatterns.com/learn/system-design/rest-api-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Address the thing; let the method be the verb. | 6 |
| 14 | [WebSockets and Realtime](https://bytepatterns.com/learn/system-design/websockets-and-realtime?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Keep the line open instead of redialling. | 5 |
| 15 | [Observability Basics](https://bytepatterns.com/learn/system-design/observability-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Metrics say something broke; traces say where. | 5 |

### System Design Cases

<a id="system-design-cases"></a>

[![System Design Cases](assets/modules/system-design-cases.png)](https://bytepatterns.com/learn/system-design-cases?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Design a URL shortener, a chat app, a feed — the interview round, end to end._ · 20 lessons · [open module](https://bytepatterns.com/learn/system-design-cases?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Design a URL Shortener](https://bytepatterns.com/learn/system-design-cases/design-url-shortener?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One tiny key, a hundred million long links behind it. | 6 |
| 2 | [Design a Rate Limiter](https://bytepatterns.com/learn/system-design-cases/design-rate-limiter?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The algorithm is easy; where the counter lives is the interview. | 6 |
| 3 | [Design a Chat App](https://bytepatterns.com/learn/system-design-cases/design-chat-app?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Finding the socket is harder than sending the message. | 7 |
| 4 | [Design a News Feed](https://bytepatterns.com/learn/system-design-cases/design-news-feed?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Pay at write time, at read time, or a little of both. | 7 |
| 5 | [Design a Notification System](https://bytepatterns.com/learn/system-design-cases/design-notification-system?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One event, three channels, and never the same message twice. | 6 |
| 6 | [Design Search Autocomplete](https://bytepatterns.com/learn/system-design-cases/design-search-autocomplete?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Not a search — a walk down a path somebody built last night. | 6 |
| 7 | [Design a File Storage Service](https://bytepatterns.com/learn/system-design-cases/design-file-storage?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Upload the paragraph that changed, not the ten gigabytes. | 7 |
| 8 | [Design Video Streaming](https://bytepatterns.com/learn/system-design-cases/design-video-streaming?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Transcode once, cut into segments, and let the edge carry it. | 7 |
| 9 | [Design Ride Matching](https://bytepatterns.com/learn/system-design-cases/design-ride-matching?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The write rate is the problem; the search is one cell lookup. | 7 |
| 10 | [Design a Payment Ledger](https://bytepatterns.com/learn/system-design-cases/design-payment-ledger?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Nothing is ever edited — a correction is one more line. | 7 |
| 11 | [Design a Job Scheduler](https://bytepatterns.com/learn/system-design-cases/design-job-scheduler?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The worker died mid-job. The ticket goes back on the rail. | 7 |
| 12 | [Design Geo Proximity Search](https://bytepatterns.com/learn/system-design-cases/design-geo-proximity-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two numbers, one index: fold a map down into a sorted string. | 7 |
| 13 | [Design E-commerce Inventory](https://bytepatterns.com/learn/system-design-cases/design-ecommerce-inventory?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One unit left, two carts, and only one of them may hear yes. | 7 |
| 14 | [Design Ad Click Aggregation](https://bytepatterns.com/learn/system-design-cases/design-ad-click-aggregation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The same click arrives twice, late, and out of order. | 7 |
| 15 | [Design a Distributed Cache](https://bytepatterns.com/learn/system-design-cases/design-distributed-cache?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A ring of machines where losing one moves only its own arc. | 7 |
| 16 | [Design a Key-Value Store](https://bytepatterns.com/learn/system-design-cases/design-key-value-store?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Three copies, two acks, two reads — the sets have to overlap. | 7 |
| 17 | [Design a Web Crawler](https://bytepatterns.com/learn/system-design-cases/design-web-crawler?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A billion pages, one polite knock per host, nothing fetched twice. | 7 |
| 18 | [Design a Leaderboard](https://bytepatterns.com/learn/system-design-cases/design-leaderboard?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Keep it sorted on the way in, and the top hundred is free. | 6 |
| 19 | [Design Hotel Booking](https://bytepatterns.com/learn/system-design-cases/design-hotel-booking?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Four nights or none — a partial stay is not a booking. | 7 |
| 20 | [Design a Collaborative Editor](https://bytepatterns.com/learn/system-design-cases/design-collaborative-editor?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Both typing in one paragraph, both landing on the same text. | 7 |

### Concurrency

<a id="concurrency"></a>

[![Concurrency](assets/modules/concurrency.png)](https://bytepatterns.com/learn/concurrency?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Threads, locks and races — watch the interleavings that bite._ · 10 lessons · [open module](https://bytepatterns.com/learn/concurrency?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Threads vs Processes](https://bytepatterns.com/learn/concurrency/threads-vs-processes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Shared memory, or a wall between you. | 4 |
| 2 | [Race Conditions](https://bytepatterns.com/learn/concurrency/race-conditions?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Two readers, one write survives. | 5 |
| 3 | [Locks and Mutexes](https://bytepatterns.com/learn/concurrency/locks-and-mutexes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One thread inside, everybody else waits. | 5 |
| 4 | [Deadlock](https://bytepatterns.com/learn/concurrency/deadlock?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Everyone holding what the next one needs. | 5 |
| 5 | [Thread Pools](https://bytepatterns.com/learn/concurrency/thread-pools?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hire the workers once, reuse them all day. | 4 |
| 6 | [Producer and Consumer](https://bytepatterns.com/learn/concurrency/producer-consumer?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A bounded belt between the two sides. | 5 |
| 7 | [Async and the Event Loop](https://bytepatterns.com/learn/concurrency/async-await-event-loop?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One thread, politely taking turns. | 5 |
| 8 | [Atomic Operations](https://bytepatterns.com/learn/concurrency/atomic-operations?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Indivisible: nobody sees it half-done. | 4 |
| 9 | [Semaphores](https://bytepatterns.com/learn/concurrency/semaphores?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Count the permits, not the holders. | 4 |
| 10 | [Designing Thread-Safe Code](https://bytepatterns.com/learn/concurrency/designing-thread-safe-code?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Don't share, freeze it, or guard it. | 5 |

### SQL

<a id="sql"></a>

[![SQL](assets/modules/sql.png)](https://bytepatterns.com/learn/sql?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Queries you can watch run — joins, groups, indexes, transactions._ · 10 lessons · [open module](https://bytepatterns.com/learn/sql?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [SELECT Basics](https://bytepatterns.com/learn/sql/sql-select-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Name the columns you want; the table hands them back. | 4 |
| 2 | [WHERE and Filtering](https://bytepatterns.com/learn/sql/sql-where-and-filtering?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Filter in the database, not in your application loop. | 4 |
| 3 | [ORDER BY and LIMIT](https://bytepatterns.com/learn/sql/sql-order-and-limit?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Sort once in the engine, then take only the slice you show. | 4 |
| 4 | [Aggregations & GROUP BY](https://bytepatterns.com/learn/sql/sql-aggregations-group-by?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Fold many rows into one number per group. | 5 |
| 5 | [INNER and OUTER JOINs](https://bytepatterns.com/learn/sql/sql-joins-inner-outer?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Match rows across tables — and decide who survives a miss. | 6 |
| 6 | [Subqueries](https://bytepatterns.com/learn/sql/sql-subqueries?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A query inside a query, answered before the outer one runs. | 5 |
| 7 | [Indexes](https://bytepatterns.com/learn/sql/sql-indexes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A second, sorted copy of one column that ends the full scan. | 6 |
| 8 | [Transactions & ACID](https://bytepatterns.com/learn/sql/sql-transactions-acid?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | All of the writes land, or none of them do. | 6 |
| 9 | [Query Execution Order](https://bytepatterns.com/learn/sql/sql-query-execution-order?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | SQL is written top-down but evaluated in a different order. | 5 |
| 10 | [The N+1 Query Problem](https://bytepatterns.com/learn/sql/sql-n-plus-one-problem?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One query for the list, then one more for every single row. | 5 |

## The Rest of the Loop

<a id="interview"></a>

_The two rounds that are not about algorithms: object design, and telling a true story well._

### Low-Level Design

<a id="lld"></a>

[![Low-Level Design](assets/modules/lld.png)](https://bytepatterns.com/learn/lld?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Objects, interfaces and patterns that survive the follow-up question._ · 15 lessons · [open module](https://bytepatterns.com/learn/lld?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Is Low-Level Design](https://bytepatterns.com/learn/lld/what-is-lld?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Below the boxes and arrows sit the classes that do the work. | 4 |
| 2 | [Encapsulation and Invariants](https://bytepatterns.com/learn/lld/encapsulation-and-invariants?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Hide the state so the object can never be caught in a bad one. | 5 |
| 3 | [Composition vs Inheritance](https://bytepatterns.com/learn/lld/composition-vs-inheritance?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Assemble behaviour from parts instead of freezing it in a family tree. | 5 |
| 4 | [Interfaces and Polymorphism](https://bytepatterns.com/learn/lld/interfaces-and-polymorphism?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Call one method name and let each type answer in its own way. | 5 |
| 5 | [SOLID in One Pass](https://bytepatterns.com/learn/lld/solid-overview?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Five habits that stop tomorrow's change from touching twenty files. | 5 |
| 6 | [Strategy Pattern](https://bytepatterns.com/learn/lld/strategy-pattern?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Put the part that varies in its own object and swap it at runtime. | 5 |
| 7 | [Observer Pattern](https://bytepatterns.com/learn/lld/observer-pattern?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One event, many reactions, and the source knows none of them. | 5 |
| 8 | [Factory Pattern](https://bytepatterns.com/learn/lld/factory-pattern?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Ask for what you want; one place decides which class to build. | 4 |
| 9 | [State Pattern](https://bytepatterns.com/learn/lld/state-pattern?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Same method call, different answer, because the object moved on. | 5 |
| 10 | [Designing a Parking Lot](https://bytepatterns.com/learn/lld/designing-a-parking-lot?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The classic interview warm-up, answered in objects rather than adjectives. | 6 |
| 11 | [Designing a File System](https://bytepatterns.com/learn/lld/designing-a-file-system?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One contract answered by both a leaf and a whole subtree. | 6 |
| 12 | [Elevator Controller](https://bytepatterns.com/learn/lld/elevator-controller?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The car has a direction, and the direction answers the buttons. | 6 |
| 13 | [LRU Cache](https://bytepatterns.com/learn/lld/lru-cache-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A map that can find, a list that can reorder, one object. | 6 |
| 14 | [Vending Machine](https://bytepatterns.com/learn/lld/vending-machine-design?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Four small objects, each one only answering for its own moment. | 6 |
| 15 | [Chess Board Model](https://bytepatterns.com/learn/lld/chess-board-model?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The piece owns its shape; the board owns who is standing where. | 7 |

### Behavioral

<a id="behavioral"></a>

[![Behavioral](assets/modules/behavioral.png)](https://bytepatterns.com/learn/behavioral?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_Tell true stories that carry signal — and skip the traps._ · 8 lessons · [open module](https://bytepatterns.com/learn/behavioral?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [Why Behavioral Matters](https://bytepatterns.com/learn/behavioral/why-behavioral-matters?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The round that separates two equally good coders. | 4 |
| 2 | [The STAR Method](https://bytepatterns.com/learn/behavioral/star-method?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Four blocks that make a story scoreable. | 5 |
| 3 | [Conflict Stories](https://bytepatterns.com/learn/behavioral/conflict-stories?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Disagree hard, keep the relationship. | 5 |
| 4 | [Failure Stories](https://bytepatterns.com/learn/behavioral/failure-stories?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Own it, cost it, then show what changed. | 5 |
| 5 | [Leadership and Ownership](https://bytepatterns.com/learn/behavioral/leadership-and-ownership?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Authority optional; follow-through is not. | 5 |
| 6 | [Questions to Ask](https://bytepatterns.com/learn/behavioral/questions-to-ask?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Your questions are part of the interview. | 4 |
| 7 | [Negotiation Basics](https://bytepatterns.com/learn/behavioral/negotiation-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Know your number before the call starts. | 5 |
| 8 | [Red Flags and Antipatterns](https://bytepatterns.com/learn/behavioral/red-flags-and-antipatterns?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | The habits that sink otherwise good candidates. | 4 |

## AI & ML

<a id="ai"></a>

_Embeddings, retrieval, evaluation, agents — the round that did not exist five years ago._

### AI & ML

<a id="ai-ml"></a>

[![AI & ML](assets/modules/ai-ml.png)](https://bytepatterns.com/learn/ai-ml?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

_From embeddings to agents — see how modern AI actually works._ · 15 lessons · [open module](https://bytepatterns.com/learn/ai-ml?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)

| # | Lesson | What you will see | Min |
|---|---|---|---|
| 1 | [What Is Machine Learning](https://bytepatterns.com/learn/ai-ml/what-is-machine-learning?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Learn the rule from examples instead of writing it. | 4 |
| 2 | [Training vs Inference](https://bytepatterns.com/learn/ai-ml/training-vs-inference?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Learn once, slowly. Answer many times, fast. | 4 |
| 3 | [Embeddings](https://bytepatterns.com/learn/ai-ml/embeddings?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Meaning turned into a fixed list of numbers. | 5 |
| 4 | [Cosine Similarity](https://bytepatterns.com/learn/ai-ml/cosine-similarity?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Compare direction, ignore magnitude. | 5 |
| 5 | [Tokenization](https://bytepatterns.com/learn/ai-ml/tokenization?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Models read chunks, not letters or words. | 5 |
| 6 | [Attention, Intuitively](https://bytepatterns.com/learn/ai-ml/attention-intuition?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Every position decides which others to listen to. | 5 |
| 7 | [Transformers: Big Picture](https://bytepatterns.com/learn/ai-ml/transformers-big-picture?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A stack of identical blocks refining one sequence. | 5 |
| 8 | [What Is an LLM](https://bytepatterns.com/learn/ai-ml/what-is-an-llm?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A next-token predictor trained on a lot of text. | 5 |
| 9 | [Temperature and Sampling](https://bytepatterns.com/learn/ai-ml/temperature-and-sampling?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | One distribution, many possible answers. | 5 |
| 10 | [Context Windows](https://bytepatterns.com/learn/ai-ml/context-windows?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A hard limit on what the model can see at once. | 4 |
| 11 | [Retrieval-Augmented Generation](https://bytepatterns.com/learn/ai-ml/rag-basics?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Fetch the facts first, then let the model write. | 5 |
| 12 | [Vector Databases](https://bytepatterns.com/learn/ai-ml/vector-databases?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Nearest-neighbour search that stays fast at scale. | 5 |
| 13 | [Fine-Tuning vs Prompting](https://bytepatterns.com/learn/ai-ml/fine-tuning-vs-prompting?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | Change the instructions, or change the weights. | 5 |
| 14 | [Agents and Tools](https://bytepatterns.com/learn/ai-ml/agents-and-tools?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | A model in a loop that can act and try again. | 5 |
| 15 | [Evaluating LLMs](https://bytepatterns.com/learn/ai-ml/evaluating-llms?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | If you cannot score it, you cannot improve it. | 5 |

## Practice problems

<a id="practice-problems"></a>

Original problems, each tied to the lesson that teaches its pattern. Company tags are deliberately absent — they cannot be verified.

| Topic | Problem | Difficulty | Patterns | Min |
|---|---|---|---|---|
| Arrays | [Single Stock Trade](https://bytepatterns.com/practice/arrays/single-stock-trade?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `single-pass` `running-minimum` | 15 |
| Arrays | [Drop Sorted Duplicates](https://bytepatterns.com/practice/arrays/drop-sorted-duplicates?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `two-pointers` `in-place` | 15 |
| Arrays | [Product Of Others](https://bytepatterns.com/practice/arrays/product-of-others?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `prefix-products` `two-pass` | 25 |
| Arrays | [Longest Distinct Run](https://bytepatterns.com/practice/arrays/longest-distinct-run?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `sliding-window` `hash-map` | 25 |
| Arrays | [Window Maximums](https://bytepatterns.com/practice/arrays/window-maximums?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `sliding-window` `monotonic-deque` | 40 |
| Arrays | [Majority Value](https://bytepatterns.com/practice/arrays/majority-value-finder?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `counting` `single-pass` | 15 |
| Arrays | [Rotate Right By K](https://bytepatterns.com/practice/arrays/rotate-right-by-k?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `in-place` `reversal` | 25 |
| Arrays | [Spiral Grid Walk](https://bytepatterns.com/practice/arrays/spiral-grid-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `matrix-traversal` `boundary-shrinking` | 25 |
| Strings | [Longest Shared Prefix](https://bytepatterns.com/practice/strings/longest-shared-prefix?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `column-scan` `string-comparison` | 15 |
| Strings | [First Unique Character](https://bytepatterns.com/practice/strings/first-unique-character?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `hash-map` `two-pass` | 15 |
| Strings | [Run Length Compression](https://bytepatterns.com/practice/strings/run-length-compression?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `two-pointers` `run-length-encoding` | 25 |
| Strings | [Multiply Digit Strings](https://bytepatterns.com/practice/strings/multiply-digit-strings?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `digit-arithmetic` `carry-propagation` | 30 |
| Strings | [Minimum Window Cover](https://bytepatterns.com/practice/strings/minimum-window-cover?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `sliding-window` `hash-map` | 45 |
| Strings | [Group Anagrams Together](https://bytepatterns.com/practice/strings/group-anagrams-together?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `hash-map` `canonical-form` | 20 |
| Strings | [Repeated DNA Sequences](https://bytepatterns.com/practice/strings/repeated-dna-sequences?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `rolling-hash` `hash-set` | 30 |
| Searching | [Integer Square Root](https://bytepatterns.com/practice/searching/integer-square-root?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `binary-search` `monotonic-predicate` | 20 |
| Searching | [Peak In Bumpy List](https://bytepatterns.com/practice/searching/peak-in-bumpy-list?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `binary-search` `slope-following` | 30 |
| Searching | [Median Of Two Sorted Lists](https://bytepatterns.com/practice/searching/median-of-two-sorted-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `binary-search` `partitioning` | 50 |
| Searching | [First And Last Occurrence](https://bytepatterns.com/practice/searching/first-and-last-occurrence?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `binary-search` `boundary-search` | 25 |
| Searching | [Minimum Daily Capacity](https://bytepatterns.com/practice/searching/minimum-daily-capacity?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `binary-search-on-answer` `greedy-check` | 30 |
| Sorting | [Out Of Place Count](https://bytepatterns.com/practice/sorting/out-of-place-count?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `sorting` `pairwise-comparison` | 15 |
| Sorting | [Three Way Flag Sort](https://bytepatterns.com/practice/sorting/three-way-flag-sort?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dutch-national-flag` `in-place` | 30 |
| Sorting | [Largest Number Arrangement](https://bytepatterns.com/practice/sorting/largest-number-arrangement?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `custom-comparator` `sorting` | 30 |
| Sorting | [H Index From Citations](https://bytepatterns.com/practice/sorting/h-index-citations?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `sorting` `counting` | 20 |
| Sorting | [Maximum Gap Buckets](https://bytepatterns.com/practice/sorting/maximum-gap-buckets?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `bucket-sort` `pigeonhole` | 40 |
| Linked Lists | [Merge Sorted Chains](https://bytepatterns.com/practice/linked-lists/merge-sorted-chains?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `two-pointers` `dummy-node` | 20 |
| Linked Lists | [Drop Nth From End](https://bytepatterns.com/practice/linked-lists/drop-nth-from-end?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `fast-slow-pointers` `dummy-node` | 25 |
| Linked Lists | [Weave List Halves](https://bytepatterns.com/practice/linked-lists/weave-list-halves?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `fast-slow-pointers` `list-reversal` | 35 |
| Linked Lists | [Remove Value Nodes](https://bytepatterns.com/practice/linked-lists/remove-value-nodes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `dummy-node` `pointer-relinking` | 15 |
| Linked Lists | [Add Two Digit Chains](https://bytepatterns.com/practice/linked-lists/add-two-digit-chains?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dummy-node` `carry-propagation` | 25 |
| Linked Lists | [Partition Around Value](https://bytepatterns.com/practice/linked-lists/partition-around-value?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dummy-node` `list-splitting` | 30 |
| Stacks & Queues | [Constant Time Min Stack](https://bytepatterns.com/practice/stacks-queues/constant-time-min-stack?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `stack` `auxiliary-stack` | 20 |
| Stacks & Queues | [Days Until Warmer](https://bytepatterns.com/practice/stacks-queues/days-until-warmer?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `monotonic-stack` | 30 |
| Stacks & Queues | [Collapse Adjacent Pairs](https://bytepatterns.com/practice/stacks-queues/collapse-adjacent-pairs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `stack` `string-scan` | 15 |
| Stacks & Queues | [Decode Nested Repeats](https://bytepatterns.com/practice/stacks-queues/decode-nested-repeats?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `stack` `string-parsing` | 30 |
| Stacks & Queues | [Largest Bar Rectangle](https://bytepatterns.com/practice/stacks-queues/largest-bar-rectangle?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `monotonic-stack` | 45 |
| Hash Tables | [Repeated Value Check](https://bytepatterns.com/practice/hash-tables/repeated-value-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `hash-set` `single-pass` | 10 |
| Hash Tables | [Subarrays Summing To K](https://bytepatterns.com/practice/hash-tables/subarrays-summing-to-k?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `prefix-sums` `hash-map` | 30 |
| Hash Tables | [Longest Consecutive Run](https://bytepatterns.com/practice/hash-tables/longest-consecutive-run?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `hash-set` `counting` | 30 |
| Hash Tables | [Shared Values Of Two Lists](https://bytepatterns.com/practice/hash-tables/shared-values-of-two-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `hash-set` `membership-test` | 15 |
| Hash Tables | [Consistent Renaming Check](https://bytepatterns.com/practice/hash-tables/consistent-renaming-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `hash-map` `bijection` | 20 |
| Hash Tables | [Four List Zero Tuples](https://bytepatterns.com/practice/hash-tables/four-list-zero-tuples?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `hash-map` `meet-in-the-middle` | 30 |
| Recursion | [Flatten a Nested List](https://bytepatterns.com/practice/recursion/flatten-nested-counts?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `recursion` `tree-walk` | 15 |
| Recursion | [Disc Tower Moves](https://bytepatterns.com/practice/recursion/disc-tower-moves?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `recursion` `divide-and-conquer` | 20 |
| Recursion | [Fast Power](https://bytepatterns.com/practice/recursion/fast-power-of-a-number?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `recursion` `divide-and-conquer` | 20 |
| Backtracking | [Phone Keypad Words](https://bytepatterns.com/practice/backtracking/phone-keypad-words?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `backtracking` `decision-tree` | 20 |
| Backtracking | [Combinations That Sum](https://bytepatterns.com/practice/backtracking/combinations-summing-to-target?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `backtracking` `pruning` | 25 |
| Backtracking | [Split Into Palindromes](https://bytepatterns.com/practice/backtracking/split-into-palindrome-pieces?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `backtracking` `pruning` | 25 |
| Greedy | [Fewest Removals to Unclash](https://bytepatterns.com/practice/greedy/fewest-removals-to-unclash?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `greedy` `interval-scheduling` `sorting` | 20 |
| Greedy | [Fewest Hops to the End](https://bytepatterns.com/practice/greedy/fewest-hops-to-the-end?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `greedy` `reach-frontier` | 20 |
| Greedy | [Split String Into Blocks](https://bytepatterns.com/practice/greedy/split-string-into-blocks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `greedy` `last-occurrence` | 20 |
| Trees & BST | [Deepest Level Count](https://bytepatterns.com/practice/trees/deepest-level-count?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `dfs` `recursion` | 15 |
| Trees & BST | [Zigzag Level Walk](https://bytepatterns.com/practice/trees/zigzag-level-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bfs` `level-order` | 30 |
| Trees & BST | [Right Edge View](https://bytepatterns.com/practice/trees/right-edge-view?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bfs` `level-order` | 25 |
| Trees & BST | [Mirror Symmetry Check](https://bytepatterns.com/practice/trees/mirror-symmetry-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `recursion` `paired-traversal` | 20 |
| Trees & BST | [Root To Leaf Target Sum](https://bytepatterns.com/practice/trees/root-to-leaf-target-sum?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `dfs` `recursion` | 20 |
| Trees & BST | [Widest Node To Node Path](https://bytepatterns.com/practice/trees/widest-node-to-node-path?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dfs` `post-order` | 30 |
| Trees & BST | [Rebuild From Two Walks](https://bytepatterns.com/practice/trees/rebuild-from-two-walks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `divide-and-conquer` `hash-map` `recursion` | 45 |
| Tries | [Wildcard Word Search](https://bytepatterns.com/practice/tries/wildcard-word-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `trie` `backtracking` | 30 |
| Tries | [Replace Words With Roots](https://bytepatterns.com/practice/tries/replace-words-with-roots?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `trie` `prefix-match` | 25 |
| Tries | [Maximum XOR Pair](https://bytepatterns.com/practice/tries/maximum-xor-pair?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `bit-trie` `greedy` | 40 |
| Heaps | [Kth Largest Value](https://bytepatterns.com/practice/heaps/kth-largest-value?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `min-heap` `top-k` | 25 |
| Heaps | [Smash Heaviest Stones](https://bytepatterns.com/practice/heaps/smash-heaviest-stones?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `max-heap` `simulation` | 20 |
| Heaps | [Closest Points To Origin](https://bytepatterns.com/practice/heaps/closest-points-to-origin?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `max-heap` `top-k` | 30 |
| Heaps | [Running Median Stream](https://bytepatterns.com/practice/heaps/running-median-stream?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `two-heaps` `streaming` | 45 |
| Heaps | [Task Scheduler Cooldown](https://bytepatterns.com/practice/heaps/task-scheduler-cooldown?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `heap` `greedy` | 35 |
| Heaps | [Reorganize String Gaps](https://bytepatterns.com/practice/heaps/reorganize-string-gaps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `heap` `greedy` | 30 |
| Two Heaps & K-Way Merge | [Kth Smallest In Matrix](https://bytepatterns.com/practice/two-heaps-k-way/kth-smallest-in-sorted-matrix?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `k-way-merge` `heap` | 30 |
| Two Heaps & K-Way Merge | [Smallest Range K Lists](https://bytepatterns.com/practice/two-heaps-k-way/smallest-range-k-lists?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `k-way-merge` `sliding-window` | 45 |
| Two Heaps & K-Way Merge | [Capital Project Picks](https://bytepatterns.com/practice/two-heaps-k-way/capital-project-picks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `two-heaps` `greedy` | 40 |
| Graphs | [Count Island Blobs](https://bytepatterns.com/practice/graphs/count-island-blobs?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dfs` `flood-fill` `grid-traversal` | 30 |
| Graphs | [Course Order Feasibility](https://bytepatterns.com/practice/graphs/course-order-feasibility?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `topological-sort` `cycle-detection` | 35 |
| Graphs | [Word Ladder Steps](https://bytepatterns.com/practice/graphs/word-ladder-steps?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `bfs` `shortest-path` | 45 |
| Graphs | [Trusted Town Judge](https://bytepatterns.com/practice/graphs/trusted-town-judge?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `degree-counting` `directed-graph` | 15 |
| Graphs | [Deep Copy A Graph](https://bytepatterns.com/practice/graphs/deep-copy-a-graph?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `dfs` `hash-map` | 30 |
| Graphs | [Spreading Rot Minutes](https://bytepatterns.com/practice/graphs/spreading-rot-minutes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bfs` `multi-source` `grid-traversal` | 30 |
| Graphs | [Two Colour Split Check](https://bytepatterns.com/practice/graphs/two-colour-split-check?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bfs` `graph-colouring` | 30 |
| Matrix & Grid | [Perimeter Of An Island](https://bytepatterns.com/practice/matrix-grid/island-perimeter-walk?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `grid-scan` `neighbour-check` | 20 |
| Matrix & Grid | [Zero Out Rows And Columns](https://bytepatterns.com/practice/matrix-grid/zero-out-rows-and-columns?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `grid-marking` `in-place` | 25 |
| Matrix & Grid | [Search A Sorted Grid](https://bytepatterns.com/practice/matrix-grid/staircase-grid-search?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `staircase-walk` `grid-search` | 25 |
| Union-Find | [Count Provinces](https://bytepatterns.com/practice/union-find/count-provinces?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `union-find` `connected-components` | 25 |
| Union-Find | [Redundant Connection](https://bytepatterns.com/practice/union-find/redundant-connection?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `union-find` `cycle-detection` | 25 |
| Union-Find | [Accounts Merge By Email](https://bytepatterns.com/practice/union-find/accounts-merge-emails?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `union-find` `hash-map` | 45 |
| Intervals | [Non Overlapping Removals](https://bytepatterns.com/practice/intervals/non-overlapping-removals?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `intervals` `greedy` | 25 |
| Intervals | [Employee Free Time](https://bytepatterns.com/practice/intervals/employee-free-time?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `intervals` `merge` | 40 |
| Intervals | [Car Pooling Capacity](https://bytepatterns.com/practice/intervals/car-pooling-capacity?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `intervals` `sweep-line` | 25 |
| Bit Manipulation | [Reverse Bit Order](https://bytepatterns.com/practice/bit-manipulation/reverse-bit-order?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `bit-shifting` `accumulator` | 20 |
| Bit Manipulation | [Single Value Among Triples](https://bytepatterns.com/practice/bit-manipulation/single-value-among-triples?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bit-counting` `modular-arithmetic` | 30 |
| Bit Manipulation | [The Missing Value](https://bytepatterns.com/practice/bit-manipulation/missing-value-in-range?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `xor-cancel` `single-pass` | 20 |
| Math & Number Theory | [Trailing Zeros Of A Factorial](https://bytepatterns.com/practice/math-number-theory/factorial-trailing-zeros?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `factor-counting` `math` | 20 |
| Math & Number Theory | [Primes Below A Limit](https://bytepatterns.com/practice/math-number-theory/primes-below-limit?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `sieve` `precomputation` | 25 |
| Math & Number Theory | [Power Under A Modulus](https://bytepatterns.com/practice/math-number-theory/power-under-modulus?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `fast-exponentiation` `modular-arithmetic` | 25 |
| Dynamic Programming | [Cheapest Stair Climb](https://bytepatterns.com/practice/dynamic-programming/cheapest-stair-climb?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `bottom-up-dp` `rolling-variables` | 20 |
| Dynamic Programming | [Grid Paths With Blocks](https://bytepatterns.com/practice/dynamic-programming/grid-paths-with-blocks?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `grid-dp` `bottom-up-dp` | 30 |
| Dynamic Programming | [Sentence Segmentation](https://bytepatterns.com/practice/dynamic-programming/sentence-segmentation?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bottom-up-dp` `hash-set` | 30 |
| Dynamic Programming | [Trading With Cooldown](https://bytepatterns.com/practice/dynamic-programming/trading-with-cooldown?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `state-machine-dp` `rolling-variables` | 45 |
| Dynamic Programming | [Paint Houses Cheaply](https://bytepatterns.com/practice/dynamic-programming/paint-houses-cheaply?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | easy | `bottom-up-dp` `rolling-variables` | 20 |
| Dynamic Programming | [Decode Digit Message](https://bytepatterns.com/practice/dynamic-programming/decode-digit-message?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bottom-up-dp` `rolling-variables` | 30 |
| Dynamic Programming | [Unique BST Shapes](https://bytepatterns.com/practice/dynamic-programming/unique-bst-shapes?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | medium | `bottom-up-dp` `counting` | 30 |
| Dynamic Programming | [Pop Balloons For Coins](https://bytepatterns.com/practice/dynamic-programming/pop-balloons-for-coins?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) | hard | `interval-dp` `bottom-up-dp` | 50 |

## Follow along

New lessons ship every few weeks and each one becomes a short animated video.

- Website: [bytepatterns.com](https://bytepatterns.com?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap)
- YouTube: [@bytepatterns](https://www.youtube.com/@bytepatterns)
- Instagram: [@bytepatterns](https://www.instagram.com/bytepatterns/)
- TikTok: [@bytepatterns](https://www.tiktok.com/@bytepatterns)
- Email updates: [bytepatterns.com](https://bytepatterns.com?utm_source=github&utm_medium=readme&utm_campaign=visual-dsa-roadmap) (one address, used only to tell you when a module ships)

## About this repository

Generated from the lesson and problem metadata that powers bytepatterns.com. Lesson text, animations, exercises and solutions live on the site; this repository holds the map, the module cards and `roadmap.json`. Found a mistake in a one-liner or a broken link? Open an issue.

Licensed under [CC BY-NC-ND 4.0](LICENSE). © BytePatterns.
