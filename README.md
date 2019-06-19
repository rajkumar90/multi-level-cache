1. Different levels of cache that are chained (L1 -> L2 -> L3 -> L4 ...)
2. Each cache level has a specific CAPACITY, READ_TIME, WRITE_TIME
3. Values at each level is a subset of values at lower level
4. For Reads, if a value is not found at a particular level, try getting it from lower levels. Also, once a value is found, it needs to be updated in higher levels as well
5. For each read, print the value along with the total time it took to read the value
6. For each write, print the time it took to write the value (Choose in what levels the value has to be written)
