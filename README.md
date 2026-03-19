# MCE SQL Playground

A browser-based SQL playground for Salesforce Marketing Cloud Engagement (MCE), built for the ListEngage Academy SQL curriculum.

## Features

- **In-browser SQL engine** powered by [sql.js](https://sql.js.org/) (SQLite via WebAssembly)
- **CSV Upload** — upload any Data Extension as a CSV and query it instantly
- **3 Query Tabs** — work on multiple queries simultaneously
- **Sample Queries** — pre-built examples for every SQL topic covered in class
- **SQL Function Footer** — 12 categories of clickable snippets that insert directly into the editor
- **Schema Viewer** — inspect loaded table structures at a glance
- **Syntax Highlighting** — powered by CodeMirror with SQL mode

## SQL Topics Covered

| Category | Functions / Concepts |
|---|---|
| SELECT | SELECT, DISTINCT, TOP, TOP PERCENT, aliases, ORDER BY, OFFSET/FETCH |
| FILTERING | WHERE, =, <>, BETWEEN, IN, IS NULL, LIKE |
| LOGIC | AND, OR, NOT |
| STRING | CONCAT, UPPER, LOWER, TRIM, LEN, CHARINDEX, SUBSTRING, REPLACE, STUFF |
| DATE | GETDATE, DATEPART, DATENAME, DATEDIFF, DATEADD, CONVERT |
| CONVERT | CAST, CONVERT, NULLIF |
| AGGREGATE | COUNT, SUM, AVG, MIN, MAX, ROUND |
| GROUP BY | GROUP BY, HAVING, ROLLUP, CUBE |
| CASE | Simple CASE, Searched CASE, CASE in GROUP BY |
| JOINS | INNER, LEFT, RIGHT, FULL OUTER, INTERSECT |
| WINDOW | RANK, DENSE_RANK, ROW_NUMBER, PARTITION BY, ROWS BETWEEN |
| SFMC | ent. prefix, Data Views, Automation Studio patterns |

## Usage

Open `index.html` directly in a browser — no server required.

Or serve locally:
```bash
npx serve .
```

## Files

- `index.html` — the full single-file application
- `AcademyImage_WhiteText.png` — ListEngage Academy logo (nav)
- `AcademyImage_AKey.png` — ListEngage Academy favicon
