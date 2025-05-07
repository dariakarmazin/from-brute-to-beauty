# from-brute-to-beauty

# Smarter Search: Designing Efficient Algorithms for Sorted Arrays 

This repo explores algorithmic strategies to solve a classic search problem — finding the first and last position of a target value in a sorted array, and counting its total occurrences.

While the problem seems simple, the way you solve it says a lot about how you approach efficiency, edge cases, and trade-offs in product design. This notebook walks through two solutions:
1. a brute-force method;
2. and a binary search approach,
and then compares their logic, clarity, and performance.

---

## 1. Problem Definition

You're given a sorted list of integers and a target value. Your task is to return:

1. The index of the first appearance of the target
2. The index of the last appearance
3. The total count of times the target appears

This type of problem shows up frequently in real systems:
- Searching logs for a specific status code range
- Counting views of a video within a certain time window
- Identifying price trends in ordered datasets

---

## 2. Solution Specification

### Method 1: Brute-force (Linear Search)
This solution checks every element in the list. It’s simple, readable, and gets the job done, but not scalable for large datasets.

### Method 2: Binary Search
This optimized method uses binary search to:
- Find the first and last positions of the target in O(log n) time
- Count occurrences by computing `last_index - first_index + 1`
- Gracefully handle edge cases (e.g., no matches)

### Comparison
- Performance boost with binary search
- Cleaner separation of concerns through modular functions
- Scalability with large arrays
- Annotated step-by-step explanations in the notebook

---

## 3. What You’ll Find in This Repo

- Problem framing and edge case analysis
- Reusable Python functions with clear input/output behavior
- Markdown walkthroughs and logic breakdowns
- [[Loom video walkthrough for binary search](https://www.loom.com/share/43c458b8616b4f6bb3ab758afe59f884?sid=558ff883-7616-4b2d-a8b7-16f5c4c61615)]
- [[Loom video walkthrough for ternary search](https://www.loom.com/share/82deb6dade1e41b29b0c96607f7ce814?sid=519ec03a-865d-41e7-985b-af5b476e7269)]

---

## 4. Why This Project?

This notebook isn’t just about finding numbers. It’s about learning to:
- Break down a user goal into testable requirements
- Choose the right algorithm for the job
- Communicate the “why” behind your solution

These are exactly the kinds of skills product managers and engineers use every day.

---

