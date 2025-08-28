
          Two Sum

          - Summary: This algorithm utilizes a hashmap (dictionary in Python) to efficiently find two numbers within a list that sum up to a target value. It iterates through the input list, checking for each number if its complement (target - number) exists in the hashmap. If found, it immediately returns the indices of the two numbers. Otherwise, it adds the current number and its index to the hashmap and continues. If no pair is found after iterating through the entire list, it returns an empty list.

          - Time Complexity: O(n) because the algorithm iterates through the input list once. Hashmap lookups have an average time complexity of O(1).
          - Space Complexity: O(n) because in the worst-case scenario, the hashmap might store all the elements from the input list.
          