# Database format

Starting with En Croissant 0.16.0, game databases use [DuckDB](https://duckdb.org/) and are stored as `.duckdb` files. You can query game metadata such as player names, ratings, and results directly with SQL.

## Upgrading a SQLite database

On the **Databases** page, select your existing `.db3` game database and click **Convert database**. En Croissant creates a separate `.duckdb` file alongside the original.

For the Lichess puzzle collection, download the DuckDB edition from the **Puzzles** tab.

## Schema and move encoding

The [game database schema](https://github.com/franciscoBSalgueiro/en-croissant/blob/29d410ebb230c3d2fdad5b4fe38656313e82f0f9/src-tauri/src/db/init-database.sql) defines the `games` table. Moves and variations use [AIX](https://github.com/franciscoBSalgueiro/aix) compression and are stored in the `movedata` column. Comments and annotation symbols are stored separately in the `annotations` column.

To read the moves and annotations in another chess program, use **Export to PGN** from the database page.
