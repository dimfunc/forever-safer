## AtomicPoll
This benchmark test tests from three aspects: `normal getting time`, `usize exceeding correction time`, and `id recycling and reuse time`.

### Normal Getting Time
**100 Times.**

Total time consumption: 21170ns (0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_100.png)

**1000 Times.**

Total time consumption: 159859ns (0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_1000.png)

**10000 Times.**

Total time consumption: 1300146ns (1ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_10000.png)

**100000 Times.**

Total time consumption: 12929758ns (12ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/normal_getting_time_100000.png)

### USize Exceeding Correction Time
The average time spent in **200 tests** is: 244261ns (0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/usize_exceeding_correction_time_200.png)

### ID Recycling and Reuse Time
**Child Benchmark** Release ID Time.

The average time spent in **200 tests** is: 39951ns (0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/id_recycling_and_reuse_time_release_200.png)

**Child Benchmark** Reuse ID Time.

The average time spent in **200 tests** is: 24933ns (0ms).

![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/id_recycling_and_reuse_time_reuse_200.png)


## InstantBus
This benchmark test will test the reception delay of different numbers of receivers (core).

### 1 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_1.png)
### 16 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_16.png)
### 32 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_32.png)
### 64 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_64.png)
### 128 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_128.png)
### 256 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_256.png)
### 512 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_512.png)
### 1024 Cores / Receivers
![Benchmark](https://raw.githubusercontent.com/dimfunc/forever-safer/benchmarks/images/instant_bus_1024.png)