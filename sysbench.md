## Command

- sysbench cpu --cpu-max-prime=20000 --threads=12 --time=0 --events=100000 run

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
