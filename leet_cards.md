<!-- flashcard 1 -->

## Card

Sliding Window UseCases

%

- Finding subarrays with specific properties (e.g., max sum, exact length).  
- Problems like "Longest Substring Without Repeating Characters."  

<!-- end flashcard 1 -->

<!-- flashcard 2 -->

## Card

Sliding Window Implementation

%

- Use two pointers to define a window.  
- Adjust window size dynamically based on constraints.  

<!-- end flashcard 2 -->


<!-- flashcard 3 -->

## Card

Two Pointers UseCases

%

- Searching pairs in sorted arrays (e.g., "Two Sum II").  
- Problems like "3Sum" or "Container with Most Water."  

<!-- end flashcard 3 -->

<!-- flashcard 4 -->

## Card

Two Pointers Implementation

%

- Initialize pointers at different positions (start/end or same side).  
- Move pointers based on conditions (e.g., sum, difference).  

<!-- end flashcard 4 -->


<!-- flashcard 5 -->

## Card

Fast and Slow Pointers UseCases

%

- Detecting cycles in linked lists or arrays.  
- Finding the middle of a linked list.  

<!-- end flashcard 5 -->

<!-- flashcard 6 -->

## Card

Fast and Slow Pointers Implementation

%

- Use two pointers; one moves 1 step, the other 2 steps.  
- Check for overlap to detect cycles or stop at the middle.  

<!-- end flashcard 6 -->


<!-- flashcard 7 -->

## Card

Merge Intervals UseCases

%

- Merging overlapping intervals (e.g., meeting rooms).  
- Problems like "Insert Interval" or "Meeting Rooms II."  

<!-- end flashcard 7 -->

<!-- flashcard 8 -->

## Card

Merge Intervals Implementation

%

- Sort intervals by start time.  
- Merge intervals when they overlap by adjusting the end time.  

<!-- end flashcard 8 -->


<!-- flashcard 9 -->

## Card

Cyclic Sort UseCases

%

- Finding missing, duplicate, or corrupt numbers in a range.  
- Problems like "Find All Numbers Disappeared in an Array."  

<!-- end flashcard 9 -->

<!-- flashcard 10 -->

## Card

Cyclic Sort Implementation

%

- Iterate through array, swapping elements to their correct positions.  
- Check for misplacements to find duplicates/missing elements.  

<!-- end flashcard 10 -->


<!-- flashcard 11 -->

## Card

In-place Reversal UseCases

%

- Reversing linked list segments (e.g., reversing between positions).  
- Problems like "Reverse Linked List II."  

<!-- end flashcard 11 -->

<!-- flashcard 12 -->

## Card

In-place Reversal Implementation

%

- Reverse pointers between specific positions in the list.  
- Use a previous node pointer to reconnect reversed parts.  

<!-- end flashcard 12 -->


<!-- flashcard 13 -->

## Card

Tree BFS UseCases

%

- Level order traversal in binary trees.  
- Finding the shortest path in unweighted graphs.  

<!-- end flashcard 13 -->

<!-- flashcard 14 -->

## Card

Tree BFS Implementation

%

- Use a queue to traverse tree levels.  
- Process nodes level by level while adding children to the queue.  

<!-- end flashcard 14 -->


<!-- flashcard 15 -->

## Card

Tree DFS UseCases

%

- Exploring all tree paths (e.g., path sum problems).  
- Problems like "Binary Tree Paths" or "Path Sum II."  

<!-- end flashcard 15 -->

<!-- flashcard 16 -->

## Card

Tree DFS Implementation

%

- Use recursion or a stack for traversal.  
- Process nodes in pre-order, in-order, or post-order.  

<!-- end flashcard 16 -->


<!-- flashcard 17 -->

## Card

Two Heaps UseCases

%

- Calculating the median of a data stream.  
- Problems like "Find Median from Data Stream."  

<!-- end flashcard 17 -->

<!-- flashcard 18 -->

## Card

Two Heaps Implementation

%

- Maintain a max-heap for lower half and a min-heap for upper half.  
- Balance heaps to keep size difference <= 1.  

<!-- end flashcard 18 -->


<!-- flashcard 19 -->

## Card

Subsets UseCases

%

- Generating all subsets or combinations of a set.  
- Problems like "Subsets" or "Combination Sum."  

<!-- end flashcard 19 -->

<!-- flashcard 20 -->

## Card

Subsets Implementation

%

- Use backtracking or iterative generation.  
- For each element, add it to existing subsets to form new ones.  

<!-- end flashcard 20 -->


<!-- flashcard 21 -->

## Card

Modified Binary Search UseCases

%

- Searching in sorted and rotated arrays.  
- Problems like "Search in Rotated Sorted Array."  

<!-- end flashcard 21 -->

<!-- flashcard 22 -->

## Card

Modified Binary Search Implementation

%

- Use binary search with additional conditions for rotations.  
- Narrow search range based on mid-value comparisons.  

<!-- end flashcard 22 -->

<!-- flashcard 23 -->

## Card

Top 'K' Elements UseCases

%

- Finding 'K' largest/smallest elements in a dataset.  
- Problems like "Kth Largest Element in an Array."  

<!-- end flashcard 23 -->

<!-- flashcard 24 -->

## Card

Top 'K' Elements Implementation

%

- Use a heap to maintain 'K' elements.  
- Push new elements and pop excess to keep size fixed.  

<!-- end flashcard 24 -->

<!-- flashcard 25 -->

## Card

K-way Merge UseCases

%

- Merging multiple sorted arrays or lists.  
- Problems like "Merge K Sorted Lists."  

<!-- end flashcard 25 -->

<!-- flashcard 26 -->

## Card

K-way Merge Implementation

%

- Use a min-heap to track smallest elements from each list.  
- Extract the smallest and add the next element from that list.  

<!-- end flashcard 26 -->

<!-- flashcard 27 -->

## Card

Topological Sort UseCases

%

- The problem will deal with graphs that have no directed cycles
- If you’re asked to update all objects in a sorted order
- If you have a class of objects that follow a particular order

- Problems featuring the Topological Sort pattern:

- Task scheduling (medium)
- Minimum height of a tree (hard)

<!-- end flashcard 27 -->

<!-- flashcard 28 -->

## Card

Topological Sort Implementation

%
- first get count of incoming links to all nodes. Start with nodes with 0 incoming links.
- Use DFS or Kahn's algorithm to order tasks.  
- Track in-degree or visited nodes to find valid order.  

<!-- end flashcard 28 -->



<!-- flashcard 29 -->

## Card

Union Find UseCases

%

- Detect cycles in graphs (e.g., "Graph Valid Tree")  
- Find connected components (e.g., "Number of Provinces")  
- Group similar items (e.g., "Accounts Merge")  

<!-- end flashcard 29 -->

<!-- flashcard 30 -->

## Card

Union Find Implementation

%

- Core idea: Track and merge disjoint sets efficiently  
- Use a parent array to represent the forest  
- `find(x)`: Find the root with path compression  
- `union(x, y)`: Link roots by rank or size  

<!-- end flashcard 30 -->