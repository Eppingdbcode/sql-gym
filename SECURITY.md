# Security policy

## Supported product

Security reports should concern the current public SQL Gym application.

## Reporting a vulnerability

Do not disclose an unpatched vulnerability in a public issue. Use GitHub's **Security → Report a vulnerability** function for this repository when private vulnerability reporting is enabled.

Include:

- the affected page or feature;
- a concise reproduction sequence;
- the observed and expected behavior;
- potential impact;
- screenshots with personal data and credentials removed.

Never include passwords, access tokens, private keys, personal datasets, or other secrets.

## Scope

The public application intentionally allows read-only SQL exploration. A query returning unexpected training data is not itself a vulnerability. Attempts to modify the shipped training data should be blocked and may be reported if reproducible.

