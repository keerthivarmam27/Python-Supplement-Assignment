# Python Supplement Assignment - Debug Challenge 🐛

## Overview
This repository contains **100 Python debugging problems** designed to sharpen your problem-solving skills and attention to detail. Each file contains working Python code with **one tricky error** that you need to find and fix.

## Assignment Details
- **Total Problems:** 100
- **Time per Problem:** ~5 minutes
- **Difficulty Level:** Beginner-friendly but tricky!
- **Files:** `problem_01.py` through `problem_100.py`

## Error Types You'll Encounter
- ✅ Off-by-one errors
- ✅ Type conversion issues
- ✅ Variable scope problems
- ✅ Comparison operator mistakes
- ✅ Case sensitivity bugs
- ✅ Mutable default arguments
- ✅ List reference vs copy issues
- ✅ Integer vs float division
- ✅ Loop boundary conditions
- ✅ Edge case handling

## How to Submit Your Work

### Step 1: Fork This Repository
1. Click the **Fork** button at the top-right of this page
2. This creates your own copy of the repository

### Step 2: Clone Your Fork
```bash
git clone https://github.com/PyExpo2K26/Python-Supplement-Assignment.git
cd Python-Supplement-Assignment
```

### Step 3: Solve the Problems
1. Open each `problem_XX.py` file
2. Read the code carefully
3. **Find and fix the error**
4. Test your solution to ensure it works correctly
5. Save the file

**Important:** Only fix the error! Don't rewrite the entire code.

### Step 4: Test Your Solutions
Run each file to verify it works:
```bash
python problem_01.py
python problem_02.py
# ... and so on
```

### Step 5: Commit Your Changes
After solving problems, commit your changes:
```bash
git add .
git commit -m "Solved problems 1-100"
```

You can also commit in batches:
```bash
git add problem_01.py problem_02.py problem_03.py
git commit -m "Solved problems 1-3"
```

### Step 6: Push to Your Fork
```bash
git push
```

### Step 7: Create a Pull Request
1. Go to your forked repository on GitHub
2. Click **Pull Request** → **New Pull Request**
3. Set the base repository to the original repo
4. Click **Create Pull Request**
5. Add a title: "Solutions by [Your Name]"
6. In the description, mention:
   - How many problems you solved
   - Any challenges you faced
   - Estimated time taken
7. Submit the pull request

## Submission Guidelines

### ✅ Do:
- Fix only the errors in each file
- Test each solution before committing
- Use meaningful commit messages
- Create one pull request with all your solutions
- Add comments if you found the bug particularly tricky

### ❌ Don't:
- Rewrite the entire code
- Use external libraries unless already imported
- Copy solutions from others
- Submit incomplete work without explanation
- Create multiple pull requests for the same assignment

## Tips for Success

1. **Read Carefully:** The errors are subtle - read every line
2. **Test Often:** Run the code after each fix
3. **Think Like Python:** Remember Python's indexing, type system, and syntax rules
4. **Use Print Debugging:** Add `print()` statements to understand what's happening
5. **Take Breaks:** If stuck, take a short break and return with fresh eyes
6. **Learn from Mistakes:** Each bug teaches you something new

## Common Mistakes to Watch For

```python
# Example 1: Off-by-one error
for i in range(10):  # Prints 0-9, not 1-10!
    print(i)

# Example 2: Assignment vs Comparison
if x = 5:  # Should be: if x == 5:
    print("Five")

# Example 3: Type mismatch
age = "25"
print("Age: " + age + 5)  # Can't add string and int!
```

## Grading Criteria
- **Correctness:** Does the code run without errors? (70%)
- **Code Quality:** Is only the bug fixed without unnecessary changes? (20%)
- **Submission Process:** Did you follow the fork/PR workflow correctly? (10%)

## Need Help?
- Review the error message carefully
- Use Python documentation
- Think about what the code is *trying* to do vs what it *actually* does
- Ask for hints (but try to solve it yourself first!)

## Deadline
Please submit your pull request by: **[INSERT DEADLINE DATE]**

## Questions?
If you have questions about:
- **The problems:** Open an issue in this repository
- **The submission process:** Check GitHub's documentation on forking and pull requests
- **Specific bugs:** Try debugging first, then ask for hints

---

**Good luck and happy debugging!** 🚀

Remember: Finding bugs is a crucial skill for every programmer. These exercises will make you a better coder!
