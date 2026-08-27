## Access

| role      | access |
|-----------|--------|
| Admin     | admin  |
| Developer | write  |
| QA        | triage |
| External  | read   |


## Branch rules

Enabled Enforced status for main branch

- Requite at least approval to merge
- If a new commit is pushed to an already approved MR the approval is required again
- The MR must be approved by someone other than the person who pushed it
- Status checks are required to pass before a refi is updated (no checks are defined ATM) but actions like lint, test or build should be completed before pushing.