# Rough


# AI Code Reviewer

## Purpose

AI Code Reviewer reviews source code like a senior software engineer.

Instead of only pointing out problems, it explains:
- Why an issue matters
- Its severity
- A suggested fix

The goal is to provide actionable feedback that improves code quality while avoiding unnecessary stylistic comments.

---

## What it reviews

- Correctness
- Security
- Performance
- Maintainability
- Readability

---

## What it does NOT do

- Rewrite the entire code unnecessarily
- Suggest changes based only on personal style preferences
- Invent issues when the code is acceptable

---

## Expected Output

For each issue:

- Category
- Severity
- Explanation
- Suggested Fix

If no significant issues are found, clearly state that the code looks good.