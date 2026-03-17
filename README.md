# Fischer-Heun RMQ Structure

A Python implementation of the **Fischer-Heun data structure** for Range Minimum Queries (RMQ). This project demonstrates an efficient way to compute RMQ using a **two-level approach**:  
- **Upper level:** naive RMQ on block minima  
- **Lower level:** sparse tables for each canonical block type  

It integrates concepts from previous lab exercises, including block decomposition, canonical block identification, and sparse table precomputation.

---

## Features

- Decomposes an array into fixed-size blocks  
- Generates **canonical codes** (fingerprints) for each block  
- Builds **sparse tables** for each canonical block type  
- Efficient RMQ queries within a block and across blocks  
- Handles invalid or out-of-range queries gracefully  

----
