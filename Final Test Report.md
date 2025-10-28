# 🧪 Final Group Test Report Template — Word Puzzle Game Plus

**Level:** Intermediate QA | **Week 5:** Test Management

**Course:** Software Testing & Quality Assurance
**Module:** Test Management (Week 5)
**Project Type:** Group Assessment
**Submission Date:** 2025-10-28

## Team Information

| Role          | Name | Responsibilities                                         |
| ------------- | ---- | -------------------------------------------------------- |
| Test Manager  |      | Planning, scheduling, coordination, metric tracking      |
| Risk Analyst  |      | Risk identification, prioritization, test design linkage |
| Test Executor |      | Execution, evidence capture, defect logging              |

## Group Rules

- Each student must belong to only one group.
- Duplicate membership or multiple submissions will result in invalidation.
- Every group member must contribute towards this project

## Project Overview

**System Under Test:** Word Puzzle Game Plus
**Technology Stack:** HTML, CSS, JavaScript
**Environment:** Chrome Browser (Desktop)

### Features Under Test

| Feature     | Description                         | Risk Category |
| ----------- | ----------------------------------- | ------------- |
| Reset Game  | Clears score and progress instantly |               |
| Leaderboard | Stores top 3 scores in localStorage |               |
| Bonus Round | Every 3 puzzles → doubles score    |               |

## Test Plan

### Objectives

### Scope

**In Scope:**
---------

**Out of Scope:**
-------------

### Tools & Resources

### Schedule

| Date                | Planned Duration | Phases    | Tasks                                                                       | Actual Duration | Status    |
| ------------------- | ---------------- | --------- | --------------------------------------------------------------------------- | --------------- | --------- |
| **Oct 24-25** | Morning          | Planning  | Draft Test Plan, Set up GitHub, Initial Risk Analysis,Create whatsapp group |                 | Completed |
|                     | Afternoon        | Design    | Complete Risk Analysis, Design all Test Cases                               |                 | Completed |
|                     | Evening          | Execution | Begin executing test cases and logging initial defects.                     |                 | Completed |
| **Oct 26**    | Morning          | Finalize  | Finish test execution, log all defects, monitor metrics.                    |                 | Completed |
|                     | Afternoon        | Reporting | Gather all metrics, write team reflection.                                  |                 | Completed |
|                     | Evening          | Reporting | Assemble and review final `Group_Test_Management_Report.md`. and submit   |                 | Completed |

### Risks

| ID | Risk Description                                                          | Likelihood (1-10) | Impact (1-10) | Priority | Mitigation Strategy                                                                               |
| -- | ------------------------------------------------------------------------- | ----------------- | ------------- | -------- | ------------------------------------------------------------------------------------------------- |
| R1 | 'Reset Game' button fails to clear game state or scores                   | 6                 | 9             | Medium   | Re-check state management logic; re-test after each change to reset function                      |
| R2 | 'Leaderboard' fails to save or display scores correctly from localStorage | 8                 | 10            | High     | Implement consistent localStorage key usage; clear cache before tests; re-test with boundary data |
| R3 | 'Bonus Round' points not calculated or added to total correctly           | 7                 | 8             | Medium   | Recheck the arithmetic logic; add unit test for bonus formula; verify updates after each round    |
| R4 | 'Leaderboard' data lost when browser cache is cleared                     | 5                 | 7             | Medium   | Document expected behavior; add “Save/Export” option for users if feasible                      |
| R5 | UI freezes or lag occurs when restarting multiple times                   | 4                 | 6             | Low      | Optimize DOM updates; test reset cycles ≥10 times; monitor console for performance warnings      |
| R6 | Player confusion due to unclear success/error messages                    | 5                 | 5             | Low      | Improve message text and color cues; conduct quick usability feedback test                        |

### Risk Coverage

- Tested Risks Percent:
- Untested Risks Percent:

## Test Cases

| TC-01 | Reset Game  | 1. Start new game`<br />`2. Play two rounds`<br />`3. Click Reset button                  | Score and progress reset to zero; new game starts cleanly.    | Works as expected                            | Medium (R1)   | pass                  |
| TC-02 | UI Feedback | 1. Enter incorrect word repeatedly.`<br />`2. Observe feedback message or color change. | User receives clear “Try Again” message in red              | Message unclear, color same as background    | Low (R6)      | Fail                  |
| TC-03 | Bonus Round | 1. Play three complete puzzles`<br />`2. Observe bonus round activation.              | Bonus round activates automatically; score doubles correctly. | Bonus round triggered but score not doubled. | Medium (R3)   | Fail                  |

## Defects

| ID     | Issue Title | Severity | Risk ID | Status | GitHub Link |
| ------ | ----------- | -------- | ------- | ------ | ----------- |
| BUG-01 |             |          |         |        |             |

## Metrics

- Test Case Pass Percent:
- Defect Density:
- Risk Coverage Percent:
- Regression Success Rate:

### Defect Summary

- Total Defects Logged:
- Critical High:
- Fix Rate:

## Test Control & Project Management

### Phases

| Phase | Deliverable | Actual Output | Variance | Owner |
| ----- | ----------- | ------------- | -------- | ----- |
|       |             |               |          |       |

**Progress Tracking Method:**
**Change Control Notes:**

## Lessons Learned

- Most Defect Prone Feature:
- Risk Analysis Impact:
- Team Communication Effectiveness:
- Improvements for Next Cycle:

## Attachments

## Sign Off

| Name             | Role          | Initials | Date |
| ---------------- | ------------- | -------- | ---- |
| Juliet Nakawesi  | Test Manager  | JN       |      |
| Donie Golanda    | Risk Analyst  | DG       |      |
| Maureen Muriithi | Test Executor | MM       |      |

## Overall Summary

**Statement:**

**Test Status:** ☐ Completed / ☐ In Progress / ☐ Deferred
