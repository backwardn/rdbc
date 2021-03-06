# Contributing to RDBC

RDBC is licensed under [Apache Licence, Version 2.0](/LICENSE).

Unless you explicitly state otherwise, any contribution you intentionally submit for inclusion in the work, as defined in the Apache-2.0 license, shall be licensed under Apache-2.0, without any additional terms or conditions.

# Building

Use `docker-compose up -d` to start up Postgres and MySQL containers to test against.

Use `cargo test` to run the unit tests.

# Formatting

Run the following command to format code before creating a pull request.

```bash
cargo fmt --all
```
