# Changelog

## 0.99.1 - 2024-11-09

### SQL

#### Fixed

- The **EXPLAIN** keyword not being uppercased
- Whitspaces before **SELECT/UPDATE** are removed in any case
- The line after single line comment is appended to the comment
- The `UNION (ALL|DISTINCT)` case is not being considered
