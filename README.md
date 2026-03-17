# Topic: ArrayList

AP Computer Science A

## Overview

This project covers ** ArrayList** concepts including ArrayList operations, traversal, element removal, and common algorithms. You may ONLY use `size()`, `add()`, `get()`, `set()`, and `remove()` — no `contains()`, `removeIf()`, or `Collections` class. Implement the 7 methods in `Unit7.java` and run the provided JUnit tests to verify your work.

## Getting Started

### Option 1: GitHub Codespaces (Recommended)

1. Click the green **Code** button on this repository
2. Select the **Codespaces** tab
3. Click **Create codespace on main**
4. Wait for the environment to build (~2 minutes the first time)
5. Start coding in `src/main/java/com/csplusplus/Unit7.java`

> **Note:** If the Java extension shows errors on first load, press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows) and run **"Developer: Reload Window"**. This is a one-time setup step.

### Option 2: Local Development

1. Accept the assignment via the GitHub Classroom link
2. Clone the repository using GitHub Desktop
3. Open the project in VS Code

## Running Tests

### In VS Code / Codespaces

Click the green play button next to any test method in `Unit7Test.java`, or open the **Testing** sidebar (beaker icon).



## Scoring

| # | Method | Points | Concepts |
|---|--------|--------|----------|
| 1 | `sumOfElements(ArrayList)` | 10 | ArrayList traversal, accumulator |
| 2 | `removeAllInstances(ArrayList, int)` | 10 | Removing while iterating (loop backwards!) |
| 3 | `doubleAllElements(ArrayList)` | 10 | `set()` to modify in place |
| 4 | `addIfNotPresent(ArrayList, int)` | 10 | Manual search (no `contains()`) |
| 5 | `getEvenElements(ArrayList)` | 10 | Filtering, creating new list |
| 6 | `removeElementsDivisibleBy5(ArrayList)` | 15 | Modulo operator, backwards removal |
| 7 | `reverseList(ArrayList)` | 15 | Swapping elements |
| | **Total** | **80** | |

## Important Constraint

You may **only** use these ArrayList methods: `size()`, `add()`, `get()`, `set()`, `remove()`. Do NOT use `contains()`, `indexOf()`, `removeIf()`, `Collections.sort()`, `Collections.reverse()`, or any other convenience methods.

## Common Mistakes

- Using `contains()` or `indexOf()` instead of manually looping
- Looping forwards when removing elements (causes skipped elements — loop backwards!)
- Using `==` to compare Integer objects instead of `.equals()` or unboxing
- Forgetting that `remove(int)` removes by index, not by value
- Not creating a new ArrayList for methods that should return a new list

## Submission
Submit your completed `Unit7.java` file through GitHub Classroom by the due date. Ensure that all tests pass and your code adheres to the style guidelines provided in class.

## Credit
This repo template was modified from [CS-Plus-Plus] (https://github.com/cs-plus-plus)
