# Fix flaky test in the scheduler suite

Profiling showed the resolver repeating identical lookups within a single request. Adds a small per-request memo.

Change #2 of 4 on branch `pr/20260811-121032-2-fix-flaky-test-in-the-scheduler-suite`.
