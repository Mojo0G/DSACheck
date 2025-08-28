
          Two Sum

          - Summary: This algorithm utilizes a hash map (dictionary in Python) to efficiently find two numbers within a list that sum up to a target value. It iterates through the input list, checking for each number if its complement (target - number) exists in the hash map. If found, it returns the indices of both numbers; otherwise, it adds the number and its index to the hash map. If no solution is found after iterating through the entire list, it returns an empty list.

          - Time Complexity: O(n) because the algorithm iterates through the input list once. Hash map lookups have an average time complexity of O(1).
          - Space Complexity: O(n) in the worst case because the hash map could potentially store all numbers from the input list if no solution is found before iterating through the entire list.
          