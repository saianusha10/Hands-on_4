# Hands-on_4


#for problem 1

2. Prove the time complexity of the algorithms
 
the time comlexity for this problem is O(K * N log K). The heap operations (heappush and heappop) take O(log K) time and we perform them for each element, leading to K * N total elements where K is the number of elements and N is size of array.

3. Comment on way's you could improve your implementation
   
using divide and conquer method - we can use this method to merge arrays in pairs.this can improve performance over a single heap based solution.

parallel processing - we can split the task of merging into separate threads for parallel computation if processing time is an issue.


#for problem 2

2. Prove the time complexity of the algorithms
 
The time complexity is O(N), where N is the size of the input array. We only traverse the array once, and all operations inside the loop are O(1).

3. Comment on way's you could improve your implementation
   
In-Place Optimization: The algorithm already operates in O(1) space complexity, so there is little room for improvement without altering the problem's constraints.
   
parallel processing - if we have to deal with large arrays , partitioning the array and processing the segments in parallel would be optimal.
