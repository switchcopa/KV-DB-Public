# KVDB – A Minimal JSON-backed Key-Value Store

KVDB is a simple key-value database written in C.  
It stores data in a JSON file and supports basic operations from the command line:

- `CREATE key value`  
- `SET key value`  
- `DELETE key`  
- `GET key`  

---

## 🛠️ Build

Use any C compiler (e.g. `gcc` or `clang`). Example:

```sh
# Build main program
gcc src/main.c src/kvdb.c src/cJSON.c -Iinclude -o kvdb

# Build test program
gcc tests/test_kvdb.c src/kvdb.c src/cJSON.c -Iinclude -o test_kvdb
```

## Usage 
```sh
kvdb CREATE username something
kvdb GET username
kvdb SET username "Something"
kvdb DELETE username
```
