# Drop the unused legacy adapter

Requests could previously hang forever when the upstream stopped responding. This adds an explicit timeout and surfaces it as a typed error.

Change #2 of 6 on branch `pr/20260811-121032-2-drop-the-unused-legacy-adapter`.
