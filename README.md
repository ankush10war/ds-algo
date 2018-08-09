# ds-algo

- http://blog.gainlo.co/index.php/category/coding-interview-questions
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
 - https://www.geeksforgeeks.org/find-maximum-path-sum-in-a-binary-tree/
 - https://www.geeksforgeeks.org/given-a-binary-tree-print-all-root-to-leaf-paths/

7. Rotated Array Problems
 - 

8. Multiply Large Numbers represented as Strings / Add two numbers represented by linked lists
 - Need to multiply using manual multiplication method of carry
 - http://www.geeksforgeeks.org/sum-of-two-linked-lists/

9. Boyer–Moore string search algorithm
 - 

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
 - http://www.geeksforgeeks.org/given-a-binary-tree-print-out-all-of-its-root-to-leaf-paths-one-per-line/

19. Heap
 - USAGE :: Kth Largest Element in a Stream
 
20. Sliding Window
 - 

21. Other Good Topics 
 - http://www.geeksforgeeks.org/anagram-substring-search-search-permutations/
 - http://blog.gainlo.co/index.php/2016/04/29/minimum-number-of-deletions-of-a-string/ - Use trie with overlapping subproblems
 - http://blog.gainlo.co/index.php/2016/07/12/meeting-room-scheduling-problem/
 - take a map<time, count + list<intervals>> iterate over intervals and store count and interval in map also store for all time between    start and end time. Max count means max meeting room required. Greater than 1 means overlap.
 - Search in a row wise and column wise sorted matrix - http://www.geeksforgeeks.org/search-in-row-wise-and-column-wise-sorted-matrix/
 - Find the first repeating element in an array of integers - http://www.geeksforgeeks.org/find-first-repeating-element-array-integers/
 - http://www.geeksforgeeks.org/find-first-non-repeating-character-stream-characters/
 - http://practice.geeksforgeeks.org/problems/largest-prime-factor/0

22. SORTING
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


++++++ http://www.geeksforgeeks.org/must-coding-questions-company-wise/ +++++

 - Google :
    + Subarray with given sum
    + Maximum Index
    + Finding the numbers
    + Longest valid Parentheses
    + Jumping Numbers
    + Connect Nodes at Same Level
    + Count BST nodes that lie in a given range
    + Implement LRU Cache
    + Interleaved Strings
    + Find triplets with zero sum
    + Egg Dropping Puzzle
    + Word Break Problem
    + Check if a Binary Tree contains duplicate subtrees of size 2 or more
    + Find largest word in dictionary by deleting some characters of given string
    + Modular Exponentiation (Power in Modular Arithmetic)
 
 - Facebook :
    + Subarray with given sum
    + Find all pairs with a given sum
    + Total Decoding Messages
    + Word Boggle
    + Activity Selection
    + Minimum Depth of a Binary Tree
    + Implement strstr
    + Multiply two strings
    + K-Palindrome
    + Find triplets with zero sum
    + Largest subset whose all elements are Fibonacci numbers
    + Look-and-Say Sequence
    + Converting Decimal Number lying between 1 to 3999 to Roman Numerals
    + Convert Ternary Expression to Binary Tree
    + Maximum Rectangular Area in a Histogram
 
 - Amazon :
    + K largest elements from a big file or array
    + Reverse a Linked List in groups of given size
    + Implement a stack with push(), pop() and min() in O(1) time
    + Add two numbers represented by linked lists
    + Convert a Binary tree to DLL
    + Stock span problem
    + Next larger element
    + Edit distance
    + Maximum of all subarrays of size k
    + Pythagorean Triplet
    + Print a Binary Tree in Vertical Order
    + Level order traversal
    + Smallest window in a string containing all the characters of another string
    + Find the number of islands
    + Detect and Remove Loop in a Linked List
    + Check if a binary tree is BST or not
    + Boolean Parenthesization
    + Arrange given numbers to form the biggest number
    + Implement LRU Cache
    + Maximum difference between node and its ancestor in Binary Tree

 - Microsoft :
    + Key Pair
    + Is Binary Number Multiple of 3
    + Kadane’s Algorithm
    + Missing number in array
    + Majority Element
    + Search in a Rotated Array
    + Check for BST
    + Finding middle element in a linked list
    + Root to leaf path sum
    + Reverse a linked list
    + Remove every k’th node
    + Merge 2 sorted linked list in reverse order
    + Longest Even Length Substring such that Sum of First and Second Half is same
    + k largest(or smallest) elements in an array | added Min Heap method
    + Write an Efficient Function to Convert a Binary Tree into its Mirror Tree
    + Determine if Two Trees are Identical

 - Adobe :
    + Search in a Rotated Array ### GOOD - https://www.geeksforgeeks.org/search-an-element-in-a-sorted-and-pivoted-array/
    + Subset Sum Problem ### DP / GOOD - https://www.geeksforgeeks.org/dynamic-programming-subset-sum-problem/
    + Reverse words in a given string
    + Sort an array of 0s, 1s and 2s
    + Minimum number of jumps ### DP / GOOD - https://www.geeksforgeeks.org/minimum-number-of-jumps-to-reach-end-of-a-given-array/
    + Check for BST
    + Root to leaf path sum
    + Sum Tree
    + Finding middle element in a linked list
    + Reverse a linked list
    + Level order traversal in spiral form
    + Right View of Binary Tree
    + Remove duplicate element from sorted Linked List
    + Merge Sort for Linked List
    + Count set bits in an integer

 - Oracle :
    + 0 – 1 Knapsack Problem
    + Search in a matrix
    + Power of 2
    + Palindrome
    + Root to leaf path sum
    + Kadane’s Algorithm
    + Binary Search
    + Implement Queue using Linked List
    + Connect Nodes at Same Level
    + Remove loop in Linked List
    + Implement Stack using Queues
    + Implement Queue using Stacks
    + Remove duplicate element from sorted Linked List
    + Search in a row wise and column wise sorted matrix
    + Find the first repeating element in an array of integers

 - D E Shaw :
    + Majority Element
    + Search in a Rotated Array
    + Sum of Middle Elements of two sorted arrays
    + Non Repeating Character
    + Kadane’s Algorithm
    + Intersection of two sorted Linked lists
    + Detect Loop in linked list
    + Print all nodes that don’t have sibling
    + Two Mirror Trees
    + Intersection Point in Y Shapped Linked Lists
    + Trie | (Insert and Search)
    + Implement Queue using Stacks
    + Implement Stack using Queues
    + Find the number of islands
    + Copy Set Bits in Range

 - Directi :
    + Maximum of all subarrays of size k
    + Search in a matrix
    + Word Boggle
    + Jumping Numbers
    + Transform String
    + Solve the Sudoku
    + Find Nth root of M
    + Array Pair Sum Divisibility Problem
    + Largest zigzag sequence
    + Maximum Intervals Overlap
    + Max rectangle
    + Maximum path sum
    + Maximize Dot Product
    + Excel Sheet | Part – 1
    + Probability of Knight

 - MAQ Software :
    + Sort an array of 0s, 1s and 2s
    + Permutations of a given string
    + Rotate Array by n elements
    + Non Repeating Character
    + Nth Fibonacci Number
    + Finding middle element in a linked list
    + n’th node from end of linked list
    + Detect Loop in linked list
    + Implement Queue using Stacks
    + Find Missing And Repeating
    + Find the Closest Element in BST
    + Check if a linked list is Circular Linked List
    + Reverse a String
    + Reverse words in a given string
    + Egg Dropping Puzzle

 - Yahoo :
    + First non-repeating character in a stream
    + Find median in a stream
    + Largest prime factor
    + Form coils in a matrix
    + Word Boggle
    + Largest Product Palindrome
    + Surpasser Count
    + Return two prime numbers
    + Sort a stack
    + Three way partitioning
    + LRU Cache
    + Serialize and Deserialize a Binary Tree
    + Split a Circular Linked List into two halves
    + Interleaved Strings
    + Max Sum without Adjacents

 - Walmart Labs :
    + Longest consecutive subsequence
    + Largest number in K swaps
    + k largest elements
    + Word Break
    + Find the highest occurring digit in prime numbers in a range
    + Count all possible paths from top left to bottom right
    + Minimum Platforms
    + Parenthesis Checker
    + Implement LRU Cache
    + Josephus Problem
    + Top View of Binary Tree
    + Intersection of Two Linked Lists
    + Alien Dictionary
    + Remove Loop in Linked List
    + Wildcard Pattern Matching

 - Samsung :
    + Longest Increasing Subsequence
    + Next larger element
    + Permutations of a given string
    + Next greater number set digits
    + Finding middle element in a linked list
    + Root to leaf path sum
    + Detect Loop in linked list
    + Left View of Binary Tree
    + Implement Queue using Linked List
    + Egg Dropping Puzzle
    + Total number of possible Binary Search Trees with n keys
    + Count number of bits to be flipped to convert A to B
    + Implement two stacks in an array
    + Given only a pointer/reference to a node to be deleted in a singly linked list, how do you delete it?

 - Paytm :
    + Sort an array of 0s, 1s and 2s
    + Reverse words in a given string
    + Reverse a linked list
    + Reverse a Linked List in groups of given size
    + Max Sum without Adjacents
    + Mirror Tree
    + Flattening a Linked List
    + Check for Balanced Tree
    + Find the number of islands
    + Coin Change
    + Count frequencies of all elements in array in O(1) extra space and O(n) time
    + Convert array into Zig-Zag fashion
    + Find the row with maximum number of 1s
    + Maximum Rectangular Area in a Histogram

 - Ola Cabs :
    + Kadane’s Algorithm
    + Missing number in array
    + Sort an array of 0s, 1s and 2s
    + Search in a matrix
    + Left View of Binary Tree
    + Mirror Tree
    + Connect Nodes at Same Level
    + K distance from root
    + Level order traversal in spiral form
    + Non Repeating Character
    + Find the number of islands
    + Find the character in first string that is present at minimum index in second string
    + Maximum difference between two elements such that larger element appears after the smaller number
    + Find the element that appears once in sorted array
    + Boolean Matrix Problem

 - Flipkart :
    + Kadane’s Algorithm
    + 0 – 1 Knapsack Problem
    + Inversion of array
    + Consecutive 1’s not allowed
    + Finding middle element in a linked list
    + Get minimum element from stack
    + Left View of Binary Tree
    + Add two numbers represented by linked lists
    + Connect Nodes at Same Level
    + Sum of dependencies in a graph
    + Maximum of all subarrays of size k
    + Possible words from Phone digits
    + Reverse Level Order Traversal
    + Implement Queue using Stack
    + Maximum Width of Tree

 - SAP Labs :
    + Sort an array of 0s, 1s and 2s
    + Check if a number is Bleak
    + Reverse words in a given string
    + Remove Spaces from string
    + Second Largest
    + Check if a number is power of another number
    + Reverse a linked list
    + Get minimum element from stack
    + BFS traversal of graph
    + Find median in a stream of integers
    + Quick Sort
    + GCD of Array
    + LCM And GCD
    + Heap Sort
    + Bubble Sort

 - Cisco :
    + Missing number in array
    + Reverse words in a given string
    + Permutations of a given string
    + Array to BST
    + Counbt set bits
    + Reverse a linked list
    + Level order traversal
    + Minimum Spanning Tree
    + Does array represent Heap
    + Kth largest element in a stream
    + Escape the jail
    + K’th smallest element
    + Insertion Sort
    + Bubble Sort

 - Goldman Sachs :
    + Reverse words in a given string
    + Overlapping rectangles
    + Column name from a given column number
    + Non Repeating Character
    + Total Decoding Messages
    + Sum Tree
    + Get minimum element from stack
    + Flattening a Linked List
    + Sort a stack using Recursion
    + Intersection Point in Y Shapped Linked Lists
    + Stock buy and sell
    + Egg Dropping Puzzle
    + Check for Balanced Tree
    + Check if two arrays are equal or not
    + Implement Queue using Stacks

 - MakeMyTrip :
    + Distinct palindromic substrings
    + Two water Jug problem
    + Minimum Cost Path
    + Transpose of Matrix
    + Smallest window in a string containing all the characters of another string
    + Check Mirror in N-ary tree
    + Longest Prefix Suffix
    + Maximum Difference
    + Nuts and Bolts Problem
    + N meetings in one room
    + String formation from substring
    + Longest Common Subsequence
    + Next Permutation
    + Trailing zeroes in factorial
    + Egg Dropping Puzzle

 - Snapdeal :
    + Fighting the darkness
    + Money Division
    + Group Anagrams Together
    + Pangram Strings
    + 0 – 1 Knapsack Problem
    + Longest Arithmetic Progression
    + Next greater number set digits
    + Number of Coins
    + Check If two Line segments Intersect
    + Two numbers with sum closest to zero
    + Parenthesis Checker
    + Maximum Rectangular Area in a Histogram
    + Smallest Positive missing number
    + Find the number of islands
    + Reverse a Linked List in groups of given size
