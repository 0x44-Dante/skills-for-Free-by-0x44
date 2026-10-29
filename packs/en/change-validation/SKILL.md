---
name: change-validation
description: Use for change validation in coding-agent workflows.
---
# Change Validation

A green test is useful only when it can detect a realistic defect.

1. Check repository rules, `git status`, branch and any running tests. Preserve concurrent work.
2. Define the smallest change, its invariant, acceptance conditions and negative example.
3. Exercise actual production paths with **must-pass**, **must-fail** and, where applicable, **unknown/error** tests.
4. In a disposable working copy, deliberately introduce a plausible defect. Verify the relevant test detects it. Mutation test failures must never touch production data.
5. Run focused tests, then appropriate regression tests against a stable revision. Record exit status and PASS/FAIL/SKIPPED counts.
6. Recheck the original failure and unrelated scenarios. Do not infer success from an empty error log.
7. Review the diff, docs, secret exposure and generated files. Stage exact paths; make small traceable commits. Never use blanket cleans, destructive resets or force pushes without explicit permission.
8. Report checks that could not run as NOT RUN, not as passing.

## Completion
- Change and revision:
- Positive / negative checks:
- Regression result:
- Skipped / not run:
- Remaining uncertainties:

## License / Lizenz
MIT; see repository LICENSE. Generic community edition; not a copy of private project instructions.
