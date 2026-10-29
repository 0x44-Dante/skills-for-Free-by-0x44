---
name: evidence-discipline
description: Use for evidence discipline in coding-agent workflows.
---
# Evidence Discipline

Make technical claims only within the boundaries of the evidence.

## Procedure
1. **Observed:** record exact inputs, commands, source revision, environment, date, outputs, exit code and artifact paths. If not executed, mark NOT RUN.
2. **Explained:** identify a verified mechanism and a source location. Otherwise call it a hypothesis.
3. **Claimed:** state the narrow conclusion, plus **Not claimed** for important adjacent claims.
4. Define a falsifying counterexample before testing. Run positive and negative controls where feasible.
5. Distinguish PASS, FAIL, SKIPPED, ERROR, INDETERMINATE and NOT RUN. Missing failure is not success.
6. After a fix, rerun the original reproducer and independent controls. A changed error count is not full validation.
7. Tie measurements to the exact revision, inputs and environment. Preserve old records; append dated corrections.
8. No invented runs, benchmarks, causes or confidence.

## Report
- Observed:
- Explained (verified / hypothesis):
- Counterexample:
- Claimed:
- Not claimed:
- Next decisive test:

## License / Lizenz
MIT; see repository LICENSE. Generic community edition; not a copy of private project instructions.
