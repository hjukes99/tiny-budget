# TODO (Next 24–48h)

## P0
1. Define transaction model and storage schema (JSON file format).
2. Implement `add` command for income/expense entries with validation.
3. Implement `summary` command for current month totals and net.
4. Implement `list` command for recent transactions (default last 10).
5. Add unit tests for command parsing and balance calculations.

## P1
6. Add category normalization and default categories.
7. Add date override flag for backfilling older transactions.
8. Improve CLI help text and examples.
9. Add error handling tests for malformed input and file corruption.

## P2
10. Add lightweight import command for CSV transactions.
11. Add optional pretty table output mode.
