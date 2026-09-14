# SQL Gym

SQL Gym is an interactive learning environment for practicing the SQL reasoning used in data analyst and business intelligence work.

The product focuses on understanding a database before answering business questions. Learners can explore tables, inspect structure, run read-only SQL freely, request progressive tips, inspect reference solutions, and receive explanations for common logical and syntax errors.

## Public website

The official public URL will be added here at launch.

## Languages

- English — default
- German — selectable in the application

## Learning paths

### SaaS Lab

A guided training model covering database orientation, `SELECT`, `DISTINCT`, expressions, filtering, aggregation, joins, NULL logic, grain, `CASE`, `HAVING`, date logic, subqueries, CTEs, and window functions.

### Retail Lab

A real-data lab based on a deterministic 50,000-line-item sample derived from the UCI Online Retail dataset. It includes cancellations, returns, missing customer identifiers, and uneven market coverage.

## How to use SQL Gym

1. Connect the selected training database.
2. Run `SHOW TABLES;` to discover available tables.
3. Run `DESC table_name;` to inspect columns, types, and keys.
4. Preview a small sample with `SELECT * FROM table_name LIMIT 5;`.
5. Write and run exploratory read-only queries.
6. Use **Show tip** when you need direction.
7. Use **Show solution** only when you want the complete reference query.
8. Use **Check task** when your result is ready for evaluation.

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

