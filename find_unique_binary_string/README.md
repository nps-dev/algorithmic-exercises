# Find Unique Binary String

## Problem Description

You are given an array of strings `nums` containing `n` unique binary strings, each of length `n`. Your task is to return a binary string of length `n` that does not appear in `nums`. If there are multiple valid answers, any of them is acceptable.

### Examples

#### Example 1:
**Input:**  
`nums = ["01", "10"]`  

**Output:**  
`"11"`  

**Explanation:**  
The string `"11"` does not appear in `nums`. `"00"` would also be a valid answer.

---

#### Example 2:
**Input:**  
`nums = ["00", "01"]`  

**Output:**  
`"11"`  

**Explanation:**  
The string `"11"` does not appear in `nums`. `"10"` would also be a valid answer.

---

#### Example 3:
**Input:**  
`nums = ["111", "011", "001"]`  

**Output:**  
`"101"`  

**Explanation:**  
The string `"101"` does not appear in `nums`. Other valid outputs include `"000"`, `"010"`, `"100"`, and `"110"`.

---

### Constraints
1. `n == nums.length`
2. `1 <= n <= 16`
3. `nums[i].length == n`
4. `nums[i]` contains only `'0'` or `'1'`.
5. All strings in `nums` are unique.

---

## Task Instructions

Follow these steps to complete the activity:


1. **Fork the Repository:**
   - Fork the [algorithmic-exercises](https://github.com/nps-dev/algorithmic-exercises/tree/main) repository to your own GitHub account. 
   - Name your fork `find_unique_binary_string`.

2. **Organize the Repository:**
   - Locate and delete the README file already present in the root directory of the repository:
     ```bash
     rm README.md
     ```
   - Navigate to the `find_unique_binary_string` directory within the repository.
   - Move the contents of the `find_unique_binary_string` directory to the **root directory**:
     ```bash
     mv find_unique_binary_string/* .
     ```
   - Delete the now-empty `find_unique_binary_string` folder:
     ```bash
     rmdir find_unique_binary_string
     ```

3. **Solve the Problem:**  
   Open the `find_unique_binary_string.py` file in the `find_unique_binary_string` directory and implement your solution. Ensure your code complies with all `TODO` comments within the file.

4. **Submit Your Solution:**  
   Commit your changes and push your solution to your GitHub repository.

---

## Additional Notes

- **Reference Problem:** [Find Unique Binary String](https://leetcode.com/problems/find-unique-binary-string/description/)

Happy coding! 🚀
