# PostgreSQL Notes

## Setup (Oct 3)
- Installed Postgres.app (PostgreSQL 18.6) on macOS
- Check version: `psql --version`

## Tutorial 1.3 and 1.4: Database
- Create a database: `createdb learning_tracker`
- Connect to it: `psql -d learning_tracker`
- Drop a database: `dropdb learning_tracker`

## psql basics
- Prompt shows the current database: `learning_tracker=#`
- In the docs the example database is `mydb`; I use `learning_tracker`
- Only type the command, not the prompt
- SQL commands end with `;`
- psql commands (`\l`, `\d`, `\q`) do not use `;`
- `\l` lists databases, `\d table_name` describes a table, `\q` quits psql

## Mistakes I made
- Typed the prompt (`mydb=>`) as part of the command
- Typed several commands on one line
- Forgot `;` (prompt becomes `learning_tracker-#`)
- Typed terminal commands (`mkdir`, `git`) inside psql