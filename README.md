# ds-algo

Questions ::

Good Questions - http://blog.gainlo.co/index.php/category/coding-interview-questions
			   - https://www.careercup.com/page?pid=adobe-interview-questions 

1. Find subarray with given sum / zero / Largest Sum Contiguous Subarray
 - http://www.geeksforgeeks.org/find-subarray-with-given-sum-in-array-of-integers/
 - http://www.geeksforgeeks.org/find-subarray-with-given-sum/
 - http://www.techiedelight.com/find-sub-array-with-0-sum/
 - http://www.geeksforgeeks.org/largest-sum-contiguous-subarray/
 - http://practice.geeksforgeeks.org/problems/kadanes-algorithm/0

2. Find all two elements / tripplets in an array with given / zero sum
 - http://www.geeksforgeeks.org/count-pairs-with-given-sum/
 - http://www.geeksforgeeks.org/count-number-triplets-product-equal-given-number/
 - http://www.techiedelight.com/find-triplet-given-with-given-sum/
 - Sort -> then put in map -> then iterate array from star and end -> can be done in nlogn

3. Reverse words in a given string
 - Iterate string put in stack and then make the reverse string from stack

4. Majority Element (Voting Algo)
 - http://www.geeksforgeeks.org/majority-element/

5. Is BST
 - http://www.geeksforgeeks.org/a-program-to-check-if-a-binary-tree-is-bst-or-not/

6. Maximum Path Sum in a Binary Tree / Root to leaf path sum

	https://www.geeksforgeeks.org/find-maximum-path-sum-in-a-binary-tree/
	https://www.geeksforgeeks.org/given-a-binary-tree-print-all-root-to-leaf-paths/

7. Rotated Array Problems


8. Multiply Large Numbers represented as Strings / Add two numbers represented by linked lists
 - Need to multiply using manual multiplication method of carry
 - http://www.geeksforgeeks.org/sum-of-two-linked-lists/

9. Boyer–Moore string search algorithm


10. Binary Tree Full Study
 - http://www.geeksforgeeks.org/binary-tree-data-structure/
 - Print all path of a tree
 - Diameter of a Binary Tree - Level of left tree + level of right tree + 1 (of root)
	
11. http://www.geeksforgeeks.org/find-the-two-repeating-elements-in-a-given-array/


12. Kth Largest Element in an array / stream
 - http://www.geeksforgeeks.org/k-largestor-smallest-elements-in-an-array/
 - http://www.geeksforgeeks.org/kth-largest-element-in-a-stream/
 - Best DS : Heap
 - http://www.geeksforgeeks.org/time-complexity-of-building-a-heap/
 - http://www.cs.toronto.edu/~krueger/cscB63h/w07/lectures/tut02.txt
 - https://www.youtube.com/watch?v=5iBUTMWGtIQ
 - http://www.crazyforcode.com/heap-data-structure/
 - https://en.wikipedia.org/wiki/Binary_heap
 
13. Segment Tree
 - http://www.geeksforgeeks.org/segment-tree-set-1-sum-of-given-range/
 - http://www.geeksforgeeks.org/segment-tree-set-1-range-minimum-query/
 - https://www.hackerearth.com/practice/notes/segment-tree-and-lazy-propagation/
 - USAGE :: Sum of given Range

14. TRIE
 - http://www.geeksforgeeks.org/trie-insert-and-search/
 - http://www.geeksforgeeks.org/longest-prefix-matching-a-trie-based-solution-in-java/
 - http://www.geeksforgeeks.org/implement-forward-dns-look-cache/
 - http://blog.gainlo.co/index.php/2016/04/29/minimum-number-of-deletions-of-a-string/
 - http://www.geeksforgeeks.org/data-structure-dictionary-spell-checker/
 - http://www.geeksforgeeks.org/dynamic-programming-set-32-word-break-problem/
 - USAGE :: Dictionary + Prefix Search + Spell Check

15. Maximum difference between two elements such that larger element appears after the smaller number
 - http://www.geeksforgeeks.org/maximum-difference-between-two-elements/

16. Stock buy sell
 - http://www.geeksforgeeks.org/stock-buy-sell/

17. Word Break Problem using Backtracking
 - http://www.geeksforgeeks.org/dynamic-programming-set-32-word-break-problem/
 - http://www.geeksforgeeks.org/word-break-problem-using-backtracking/
 
18. Print all paths of a binary tree
http://www.geeksforgeeks.org/given-a-binary-tree-print-out-all-of-its-root-to-leaf-paths-one-per-line/

19. Heap

 - USAGE :: Kth Largest Element in a Stream
 
20. Sliding Window


GOOD :: 

http://www.geeksforgeeks.org/anagram-substring-search-search-permutations/
http://blog.gainlo.co/index.php/2016/04/29/minimum-number-of-deletions-of-a-string/ - Use trie with overlapping subproblems
http://blog.gainlo.co/index.php/2016/07/12/meeting-room-scheduling-problem/ - take a map<time, count + list<intervals>> iterate over intervals and 
	store count and interval in map also store for all time between start and end time. Max count means max meeting room required. Greater than 1 means overlap.


::: SORTING

 - Bubble Sort (Compare two element, swap if one is taller, with this the largest element will move to right)
 
   * Complexity - O(N^2) 
   * Comparisons - O(N^2) 
   * Swaps - O(N^2) 
   * Sort in place, meaning that, besides the initial array, very little extra memory is required

 - Selection Sort (Find min, swap with first and so on) (Less number of swaps)
 
   * Complexity - O(N^2) 
   * Comparisons - O(N^2) 
   * Swaps - O(N) 
   * Sort in place, meaning that, besides the initial array, very little extra memory is required

 - Insertion Sort
 
   * Complexity - O(N^2) 
   * Comparisons - O(N^2) 
   * Swaps - O(N^2) 
   * Sort in place, meaning that, besides the initial array, very little extra memory is required

 - Merge Sort
 
   * Complexity - O(N^2) 
   * Comparisons - O(N^2) 
   * Swaps - O(N^2) 

 - Heap Sort
 
   * Complexity - O(N^2) 
   * Comparisons - O(N^2) 
   * Swaps - O(N^2) 

 - Quick Sort
 
   * Complexity - O(Nlog(N)) 
   * Algo book page 337




::: DS / ALGO BOOK



:::: Heap



:::: http://www.geeksforgeeks.org/must-coding-questions-company-wise/

 - Subarray with given sum : http://www.geeksforgeeks.org/find-subarray-with-given-sum/
 - Interleaved Strings
 - Find triplets with zero sum - Refer question 1 above
 - Egg Dropping Puzzle
 - Word Break Problem
 - Find largest word in dictionary by deleting some characters of given string
 - Find all pairs with a given sum
 - Total Decoding Messages
 - Word Boggle
 - Minimum Depth of a Binary Tree
 - Multiply two strings
 - K-Palindrome
 - Maximum Rectangular Area in a Histogram
 - Add two numbers represented by linked lists
 - Stock span problem
 - Print a Binary Tree in Vertical Order
 - Smallest window in a string containing all the characters of another string
 - Find the number of islands
 - Arrange given numbers to form the biggest number
 - Is Binary Number Multiple of 3
 - Kadane’s Algorithm - http://www.geeksforgeeks.org/largest-sum-contiguous-subarray/ +++ GOOD
 - Majority Element - http://www.geeksforgeeks.org/majority-element/ - Voting Algo  +++ GOOD
 - Search in a Rotated Array - http://www.geeksforgeeks.org/search-an-element-in-a-sorted-and-pivoted-array/ +++ GOOD
 - Root to leaf path sum
 - Write an Efficient Function to Convert a Binary Tree into its Mirror Tree
 - Determine if Two Trees are Identical
 - Subset Sum Problem - http://www.geeksforgeeks.org/dynamic-programming-subset-sum-problem/ +++ DP
 - Reverse words in a given string - http://www.geeksforgeeks.org/reverse-words-in-a-given-string/ +++ GOOD
 - Sort an array of 0s, 1s and 2s - http://www.geeksforgeeks.org/sort-an-array-of-0s-1s-and-2s/
 - Minimum number of jumps
 - Sum Tree
 - Level order traversal in spiral form
 - Right View of Binary Tree
 - 0 – 1 Knapsack Problem
 - Search in a matrix
 - Power of 2
 - Palindrome - http://www.geeksforgeeks.org/check-if-a-number-is-palindrome/
 - Connect Nodes at Same Level
 - Search in a row wise and column wise sorted matrix - http://www.geeksforgeeks.org/search-in-row-wise-and-column-wise-sorted-matrix/
 - Find the first repeating element in an array of integers - http://www.geeksforgeeks.org/find-first-repeating-element-array-integers/
 - http://www.geeksforgeeks.org/find-first-non-repeating-character-stream-characters/
 - http://practice.geeksforgeeks.org/problems/largest-prime-factor/0
