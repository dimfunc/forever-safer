## AtomicPoll
This benchmark test tests from three aspects: `self increasing time`, `usize exceeds repair time`, and `id recycling time`.

### Self Increasing
**10 Times.**

Total time consumption: 2605ns (2.60μs, 0ms).

Average time consumption: 137ns (0.14μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_10.png)

**100 Times.**

Total time consumption: 15549ns (15.55μs, 0.02ms).

Average time consumption: 109ns (0.11μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_100.png)

**1000 Times.**

Total time consumption: 131346ns (131.35μs, 0.13ms).

Average time consumption: 94ns (0.09μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_1000.png)

**10000 Times.**

Total time consumption: 1298523ns (1298.52μs, 1.30ms).

Average time consumption: 93ns (0.09μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_10000.png)

### USize Exceeds Repair Time
The average time spent in *200 tests* is: 98ns (0.10μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/usize_exceeding_correction_time_200.png)

### ID Recycling and Reuse Time
**Child Benchmark** Release ID Time.

Test at times 10, 100, 1000, 10000, 100000, 1000000.

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/id_recycling_and_reuse_time_release.png)

**Child Benchmark** Reuse ID Time.

Test at times 10, 100, 1000, 10000, 100000, 1000000.

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/id_recycling_and_reuse_time_reuse.png)


## InstantBus
This benchmark test will test the reception delay of different numbers of receivers (core).

### 1 Cores / Receivers
Average time consumption: 0ns (0μs, 0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_1.png)
### 32 Cores / Receivers
Average time consumption: 53324ns (53.32μs, 0.05ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_32.png)
### 64 Cores / Receivers
Average time consumption: 108919ns (108.92μs, 0.11ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_64.png)
### 256 Cores / Receivers
Average time consumption: 432352ns (432.35μs, 0.43ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_256.png)
### 1024 Cores / Receivers
Average time consumption: 1829667ns (1829.67μs, 1.83ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_1024.png)