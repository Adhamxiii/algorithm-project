# Job Scheduling Problem Solver

This repository contains JavaScript solutions for two variants of the Job Scheduling Problem. The first problem involves maximizing the total profit obtained from completing a set of jobs within their deadlines, and the second problem focuses on maximizing the profit earned by selecting a subset of non-overlapping jobs.

## Table of Contents

- [Job Scheduling Problem Solver](#job-scheduling-problem-solver)
  - [Table of Contents](#table-of-contents)
  - [Problem Descriptions](#problem-descriptions)
    - [Question 1](#question-1)
    - [Question 2](#question-2)
  - [Solutions](#solutions)
    - [JavaScript](#javascript)
      - [Question 1](#question-1-1)
      - [Question 2](#question-2-1)
  - [Usage](#usage)
  - [Testing](#testing)

## Problem Descriptions

### Question 1

The Job Scheduling Problem involves maximizing the total profit obtained from completing a set of jobs within their deadlines. The decision variables are the start times of each job, and the goal is to find the optimal schedule to maximize profits.

### Question 2

The second question involves maximizing the profit earned by selecting a subset of jobs from a given list. The constraint is that no two selected jobs can overlap in time. The goal is to find the optimal set of non-overlapping jobs that yields the maximum profit.

## Solutions

### JavaScript

#### Question 1

The solution for Question 1 is implemented in JavaScript. It takes a list of jobs as input and returns the maximum number of jobs done and the total profit.

#### Question 2

The solution for Question 2 is also implemented in JavaScript. It takes a list of jobs as input and returns the maximum profit that can be obtained by selecting a subset of non-overlapping jobs.

## Usage

To use the provided solutions, you can include the JavaScript code in your project and call the respective functions with the input jobs.

Example:

```javascript
// Example usage for Question 1
const Jobs1 = [[1,4,20],[2,1,10],[3,1,40],[4,1,30]];
const [jobsDone, totalProfit] = maxProfit(Jobs1);

// Example usage for Question 2
const Jobs2 = [[1,2,50],[2,1,20],[3,2,30],[4,1,10]];
const maxProfitValue = maxProfit(Jobs2);
```

## Testing
The repository includes test cases for both problem variants. You can run these test cases to ensure that the solutions work correctly.

Test cases are provided in the HTML file along with the JavaScript solutions. Each test case includes input jobs and the expected output.

```html
<p><strong>Test Case 1</strong></p>
<p><strong>Input:</strong> [[1,4,20],[2,1,10],[3,1,40],[4,1,30]]</p>
<p><strong>Expected Output:</strong> [2, 60]</p>
```