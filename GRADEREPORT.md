# Grading Report

**Final Grade: 8.20/10.00**

## Rubric

| Criterion | Points |
|-----------|--------|
| `extract_data` correctly slices, title-cases names, int conversion, extracts grades, and leaves input untouched | **1.5** |
| `curve_grades` applies the curve (while loop) and caps values at 100 | **3** |
| `print_top_performers` prints only qualifying `Name: Score` lines (>= 95) | **3** |
| Code quality (required loop choices, clear logic) | **0.7** |


## General Comments

I can see that you do have some of the core looping patterns.

I noticed that you have made a push on a previous version of your extract_data function. You may have overcomplicated a bit. I will consider your attempt on that commit so you don't get a zero for extract_data. For the other 2 functions I will use your last commit.

Your code quality can be improved by using the append function on the curve_grades and use the required while loop pattern, and use embedded indexes in the for loop in the print function.


## Functionality

- tests/test_grader.py::RosterHelperTests::test_curve_grades_values_and_clamping: Passed (10.0 points)

- tests/test_grader.py::RosterHelperTests::test_extract_data_parses_names_and_grades_title_case: Failed (0.0 points)
   Error:     AssertionError: Lists differ: [] != ['Ana Lopez', 'Priya Singh']

- tests/test_grader.py::RosterHelperTests::test_extract_data_returns_new_lists: Failed (0.0 points)
   Error:     AssertionError: Lists differ: [] != ['Max Jones']

- tests/test_grader.py::RosterHelperTests::test_print_top_performers_prints_name_and_score_for_ge_95: Passed (10.0 points)

