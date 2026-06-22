# Contributing

This repository uses a conservative workflow for code review and security-fix work.

## Before Starting Work

1. Confirm the repository, issue, or program rule is explicitly in scope.
2. Confirm the expected reward or mark it as `TBD`.
3. Record the task in the local bounty ledger before spending meaningful review time.
4. Stop if the expected token or operating cost exceeds 50% of the estimated reward.

## Development Rules

- Keep changes focused and reviewable.
- Prefer tests and documentation with every fix.
- Do not include secrets, credentials, personal data, or exploit payloads in commits.
- Avoid broad refactors unless they are required for the fix.
- Use pull requests for changes once normal source code is added.

## Security Review Rules

- Review code defensively.
- Do not run intrusive scans or generate attack traffic.
- Do not test third-party systems unless explicit authorization exists.
- Keep sensitive findings private until disclosure rules are clear.

## Pull Request Expectations

Every pull request should include:

- Scope and authorization reference.
- Summary of the change.
- Risk or security impact.
- Validation steps.
- Disclosure notes when relevant.
