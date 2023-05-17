# Leetcode
First Question
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
  You may assume that each input would have exactly one solution, and you may not use the same element twice.
  The given code finds two indices in the input array nums such that the corresponding values at those indices sum up to the given target. Here's the algorithm for the twoSum function:

  Start iterating over the array nums from index 0 to nums.length - 1 using a variable i.
  For each i, iterate over the array again from index i+1 to nums.length - 1 using a variable j.
  Check if nums[i] + nums[j] is equal to the target:
  If the sum is equal to the target, return the indices as an array new int[]{i, j}.
  If no matching pair is found, return null to indicate no solution.
  The main function reads the input size n, target value, and the array nums from the user. It then calls the twoSum function with nums and target as arguments to get the indices. Finally, it prints the indices if found or prints "noo" if no solution is found.






