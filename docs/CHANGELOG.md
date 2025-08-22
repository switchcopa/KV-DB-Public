# Changelog

All notable changes to KVDB will be documented in this file.

## [1.0.0] – 2025-08-23
### Added
- First ever MVP release of KVDB.
- Command-line interface (CLI) supporting:
  - `CREATE key value` – create a new key with a value.
  - `SET key value` – update an existing key.
  - `GET key` – retrieve a value for a key.
  - `DELETE key` – remove a key from the database.
- JSON-based persistent storage (`kvdb_store.json`).
- Basic test suite ensuring core functionality works.
- README.md with usage instructions and CLI reference.

### Notes
- This release is the minimal viable product (MVP) version.
- Only supports string key-value pairs.
- Future releases may include additional features and data types.
