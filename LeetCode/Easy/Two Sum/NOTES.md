
          Two Sum

          - Summary: This function uses an unordered_map (hash table) to efficiently find pairs of numbers that sum to a target value.  It first populates the hash table with each number in the input array and its index. Then, it iterates through the array again, checking if the complement (target - current number) exists in the hash table. If found and the complement's index is different from the current number's index, it returns the indices of the pair. Otherwise, it returns an empty vector indicating no such pair exists.

          - Time Complexity: O(n) because the algorithm involves two iterations through the input array, each taking linear time.  The hash table lookups have an average time complexity of O(1).
          - Space Complexity: O(n) because the space used by the unordered_map (hash table) is proportional to the number of elements in the input array in the worst case.
          