## Command

- sysbench cpu --cpu-max-prime=20000 --threads=<num_cores> --time=0 --events=100000 run

# Orion o6

sysbench 1.0.20 (using system LuaJIT 2.1.1767980792)

Running the test with following options:
Number of threads: 12
Initializing random number generator from current time


Prime numbers limit: 20000

Initializing worker threads...

Threads started!

CPU speed:
    events per second:  9922.64

General statistics:
    total time:                          10.0718s
    total number of events:              100000

Latency (ms):
         min:                                    0.90
         avg:                                    1.21
         max:                                   14.73
         95th percentile:                        2.18
         sum:                               120805.94

Threads fairness:
    events (avg/stddev):           8333.3333/2686.78
    execution time (avg/stddev):   10.0672/0.00

# Speedtest cli
- speedtest -s 48475

   Speedtest by Ookla

      Server: YouFibre - Manchester (id: 48475)
         ISP: BRSK
Idle Latency:    12.71 ms   (jitter: 0.18ms, low: 12.39ms, high: 12.88ms)
    Download:  4627.98 Mbps (data used: 5.7 GB)                                                   
                 68.43 ms   (jitter: 45.60ms, low: 12.49ms, high: 336.22ms)
      Upload:  4639.38 Mbps (data used: 5.2 GB)                                                   
                 13.07 ms   (jitter: 0.77ms, low: 12.26ms, high: 18.96ms)
 Packet Loss: Not available.
  Result URL: https://www.speedtest.net/result/c/2b449875-0b15-40c1-bcd1-26d15d8d4796


# Rock5bPlus

sysbench 1.0.20 (using system LuaJIT 2.1.1767980792)

Running the test with following options:
Number of threads: 8
Initializing random number generator from current time


Prime numbers limit: 20000

Initializing worker threads...

Threads started!

CPU speed:
    events per second:  5391.44

General statistics:
    total time:                          18.5460s
    total number of events:              100000

Latency (ms):
         min:                                    1.03
         avg:                                    1.48
         max:                                    5.96
         95th percentile:                        2.66
         sum:                               148333.78

Threads fairness:
    events (avg/stddev):           12500.0000/5482.51
    execution time (avg/stddev):   18.5417/0.00

# Dragonq8b

sysbench 1.0.20 (using system LuaJIT 2.1.1761786044)

Running the test with following options:
Number of threads: 8
Initializing random number generator from current time


Prime numbers limit: 20000

Initializing worker threads...

Threads started!

CPU speed:
    events per second:  9269.01

General statistics:
    total time:                          10.7876s
    total number of events:              100000

Latency (ms):
         min:                                    0.77
         avg:                                    0.86
         max:                                    6.86
         95th percentile:                        0.97
         sum:                                86275.28

Threads fairness:
    events (avg/stddev):           12500.0000/1281.31
    execution time (avg/stddev):   10.7844/0.00


# DellXPS13 9370 - i7-8550U CPU @ 1.80GHz

sysbench 1.0.20 (using system LuaJIT 2.1.1767980792)

Running the test with following options:
Number of threads: 8
Initializing random number generator from current time


Prime numbers limit: 20000

Initializing worker threads...

Threads started!

CPU speed:
    events per second:  2611.06

General statistics:
    total time:                          38.2972s
    total number of events:              100000

Latency (ms):
         min:                                    2.09
         avg:                                    3.06
         max:                                   23.30
         95th percentile:                        4.03
         sum:                               306319.98

Threads fairness:
    events (avg/stddev):           12500.0000/99.81
	execution time (avg/stddev):   38.2900/0.00

