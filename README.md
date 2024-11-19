# Concurrent Map-Reduce File Crawler

A multithreaded Go implementation of a map-reduce file crawler using workerpool pattern to process and aggregate file contents.

## Features

- Concurrent file system traversal
- Workerpool pattern for efficient resource usage
- Type-safe transformations and accumulations


## Components

### Workerpool

Implements three core operations:

- **Transform** - element processing/conversion
- **Accumulate** - value aggregation
- **List** - recursive structure traversal

### Crawler

Manages filesystem operations:

- Recursive directory traversal
- JSON file reading and parsing
- Result accumulation and combination  