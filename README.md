# SQL Gym

SQL Gym is an interactive learning environment for practicing the SQL reasoning used in data analyst and business intelligence work.

The product focuses on understanding a database before answering business questions. Learners can explore tables, inspect structure, run read-only SQL freely, request progressive tips, inspect reference solutions, and receive explanations for common logical and syntax errors.

## Public website

**[Open SQL Gym](https://sql-gym-app.pages.dev/)**

The application is free to use in a modern desktop browser. No account is required.

## Languages

- English — default
- German — selectable in the application

## Learning paths

SQL Gym offers three training paths, each with 18 exercises:

- **Beginner** — learn or refresh database orientation, core querying, joins, CTEs, and windows.
- **Advanced** — practice SQL reasoning, grain, NULL handling, dates, aggregations, and analytical patterns.
- **Pro** — analyze 50,000 genuine retail line items in realistic multi-step business problems.

### SaaS Lab

A guided training model covering database orientation, `SELECT`, `DISTINCT`, expressions, filtering, aggregation, joins, NULL logic, grain, `CASE`, `HAVING`, date logic, subqueries, CTEs, and window functions.

### Retail Lab

A real-data lab based on a deterministic 50,000-line-item sample derived from the UCI Online Retail dataset. It includes cancellations, returns, missing customer identifiers, and uneven market coverage.

## How to use SQL Gym

1. Choose **Beginner**, **Advanced**, or **Pro**.
2. Connect the selected training database when the path includes an environment exercise.
3. Run `SHOW TABLES;` to discover available tables.
4. Run `DESC table_name;` to inspect columns, types, and keys.
5. Preview a small sample with `SELECT * FROM table_name LIMIT 5;`.
6. Write and run exploratory read-only queries.
7. Use **Show tip** when you need direction.
8. Use **Show solution** only when you want the complete reference query.
9. Use **Check task** when your result is ready for evaluation.

## Keyboard shortcuts

- `Ctrl+Enter` or `Cmd+Enter`: run freely.
- `Ctrl+Shift+Enter` or `Cmd+Shift+Enter`: check the task.
- `Tab`: insert indentation in the SQL editor.
- `Escape`: close an open help panel.

## MySQL Workbench

Open **Workbench** inside SQL Gym to download the installation script for the active lab. Run the complete script in a local MySQL connection, refresh **SCHEMAS**, and begin with the same orientation workflow.

The browser application and local MySQL are separate environments. Progress is stored only in the browser and is not synchronized with Workbench.

## Documentation

- [Frequently asked questions](docs/FAQ.md)
- [Data attribution](docs/DATA_ATTRIBUTION.md)
- [Security policy](SECURITY.md)
- [Product and brand notice](BRAND_AND_COPYRIGHT.md)
- [Changelog](CHANGELOG.md)

## Repository scope

This public repository contains user documentation only. It does not contain the proprietary application source code, evaluation logic, production data package, infrastructure configuration, credentials, or deployment workflow.

Copyright © 2026 SQL Gym project owner. All rights reserved. See [BRAND_AND_COPYRIGHT.md](BRAND_AND_COPYRIGHT.md).
