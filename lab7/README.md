# Lab 7 - Git Exercises

## Exercise 1 - Personal Portfolio Conflict Simulation

### Reflection Questions

**1. Why did the conflict occur?**  
The conflict happened because the same Skills section was changed differently in both branches.

**2. What lines in the file were changed in both branches?**  
The Programming and Git lines in the Skills section were changed in both branches.

**3. What would have prevented this conflict?**  
Pulling the latest changes before editing and coordinating changes between devices could have prevented the conflict.

**4. In real life, how do you avoid conflicts when working on multiple devices?**  
I would pull before starting work, commit frequently, and push my changes regularly.

**5. What was the most challenging part of resolving the conflict?**  
The most challenging part was understanding the conflict markers and deciding how to combine both versions.

**How did Git help you identify where the conflict was?**  
Git showed conflict markers such as `<<<<<<<`, `=======`, and `>>>>>>>` around the conflicting lines.

---

## Exercise 2 - Recipe Bug Hunt with Git Bisect

### Reflection Questions

**1. How many times did you have to check the temperature before Git found the bug?**  
I checked the temperature 3 times during the bisect process.

**2. If you had 100 commits instead of 7, about how many checks would bisect need?**  
About 7 checks.

**3. How is bisect different from manually checking each commit with git checkout?**  
Git bisect uses binary search, so it checks fewer commits and finds the bug faster.

**4. When would git bisect be most useful in real projects?**  
It is useful when a bug appeared somewhere in a long commit history and I know one good commit and one bad commit.

**5. What information do you need to start a bisect session?**  
I need to know a bad commit where the bug exists and a good commit where the bug does not exist.
