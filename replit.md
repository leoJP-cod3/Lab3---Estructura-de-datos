# HashMap Lab - C Project

## Project Overview
A C-based laboratory assignment implementing a HashMap (Hash Table) data structure using linear probing for collision resolution.

## Tech Stack
- **Language**: C
- **Compiler**: GCC
- **Tools**: gdb (debugging), bash (test runner)

## Key Files
- `hashmap.h` - Header file with struct definitions and function prototypes
- `hashmap.c` - Implementation file (student exercises - stub functions to be completed)
- `main.c` - Word counter application demonstrating HashMap usage
- `test.c` - Test suite for validating the implementation
- `test.sh` - Shell script to compile and run tests

## Running the Project

### Run Tests
```bash
bash test.sh
```

### Run Word Counter
```bash
gcc main.c hashmap.c -o main && ./main
```

## HashMap Functions to Implement
1. `createMap` - Initialize the map with a given capacity
2. `insertMap` - Insert key-value pairs with linear probing collision handling
3. `searchMap` - Find a value by key
4. `eraseMap` - Soft-delete an entry (set key to NULL)
5. `firstMap` / `nextMap` - Iterators to traverse the map
6. `enlarge` - Double capacity and rehash all entries

## Workflow
- **Start application**: Runs `bash test.sh` to compile and test the implementation
