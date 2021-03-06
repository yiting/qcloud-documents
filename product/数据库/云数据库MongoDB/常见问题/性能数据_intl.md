## Performance Test Instructions

### Tool
[Yahoo! Cloud Serving Benchmark](https://github.com/brianfrankcooper/YCSB)

### Test Method
1. A single data entry is 1 KB
2. Write up to 80% of the instance capacity. For example: if the instance capacity is 100 GB, write 80 GB of data to the instance.
3. Perform 70% read and 30% update operations to get QPS (Queries Per Second) data
4. Since there can be difference between the performances under different scenarios, please select instances with the appropriate specifications according to your business demand and test data

## Performance Data of High IO Instances
| CPU | memory | QPS |
|:--:|:--:|
| 1 cores | 2 G | 3000 |
| 2 cores | 4 G | 5000 |
| 2 cores | 6 G | 6000 |
| 4 cores | 8 G | 9000 |
| 4 cores | 12 G | 14000 |
| 6 cores | 16 G | 20000 |
| 10 cores | 24 G | 25000 |
| 12 cores | 32 G | 27000 |
| 18 cores | 48 G | 30000 |
| 24 cores | 64 G | 33000 |

## Performance Data of High IO Instance (10 Gigabyte)
| CPU | Memory | Number of sets| Number of documents in a single set| Test data set (GB) | Runtime (S) | Data sampling interval (S) | Average QPS (rounded) |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 2 cores | 4 G | 2 | 100 million | 79 | 1800 | 10 | 5000 |
| 4 cores | 8 G | 3 | 100 million | 118 | 1800 | 10 | 9000 |
| 6 cores | 16 G | 6 | 100 million | 237 | 1800 | 10 | 20000 |
| 12 cores | 32 G | 6 | 200 million | 426 | 1800 | 10 | 27000 |
| 24 cores | 64 G | 15 | 200 million | 1161 | 1800 | 10 | 33000 |
| 24 cores | 128 G | 30 | 200 million | 2317 | 1800 | 10 | 36000 |
| 32 cores | 240 G | 40 | 200 million | 3031 | 1800 | 10 | 39000 |


