# Perseid

Perseid provides utilities to describe a [PostgreSQL](https://www.postgresql.org) database schema as YAML, to verify the schema against the same or a different database and to generate SQL that will modify the schema to match the YAML description.

## Features

- Outputs a YAML description of a Postgres database's tables and other objects (metadata), suitable for storing in a version control repository
- Generates SQL statements to modify a database so that it will match an input YAML/JSON specification
- Generates an augmented YAML description of a Postgres database from its catalogs and an augmentation specification.

## Requirements

- PostgreSQL 10 or higher
