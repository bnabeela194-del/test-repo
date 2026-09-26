
# Harness Report

## Task
Fix the Tribonacci test issue.

## Without Harness
| Run | Pass | Turns|Cost|
|---  |  ---  | --- |---|
| 1   | Yes   | --- | — |
| 2   | Yes   | --- | — |
| 3   | Yes   | --- | — |
| 4   | Yes   | —   | — |
| 5   | Yes   | —   | — |
| 6   | Yes   | —   | — |
| 7   | Yes   | —   | — |
| 8   | Yes   | —   | — |
| 9   | Yes   | —   | — |
| 10  | Yes   | —   | — |

## With Harness
| Run | Pass |Turns|Cost
|---  |---   |---  |---|
| 1   | Yes  | —   | — |
| 2   | Yes  | —   | — |
| 3   | Yes  | —   | — |
| 4   | Yes  | —   | — |
| 5   | Yes  | —   | — |
| 6   | Yes  | —   | — |
| 7   | Yes  | —   | — |
| 8   | Yes  | —   | — |
| 9   | Yes  | —   | — |
| 10  | Yes  | —   | — |

## Harness change
The CLAUDE.md instructions and blocking hook were added to constrain changes and require the relevant tests.

## Limitation
A harness cannot by itself guarantee that the underlying code change is correct.
The CLAUDE.md instructions and blocking hook helped keep the agent focused on fixing the Tribonacci test issue. The instructions clearly explained what the agent should do, while the blocking hook helped prevent unwanted changes. This made the work more controlled and consistent.