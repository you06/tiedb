# Benchmark

This doc tells how to run benchmark in the future.

## sysbench

````
/bench
```
workload:
  threads: 128
  repeat_time: 4
  benchtime: 240
```
````

eg. https://github.com/tikv/tikv/pull/5652#issuecomment-542123475

## tpcc

```
/bench +tpcc
```

eg. https://github.com/tikv/tikv/pull/5673#issuecomment-543111881

## tpch

````
/bench +tpch
```
workload:
  queries: 10.sql 20.sql
  repeat_time: 10
```
````

eg. https://github.com/tikv/tikv/pull/6418/#issuecomment-574509781

## ycsb

````
/bench +ycsb
```
workload:
  workload: workloada
  mode: mysql
```
````

eg. https://github.com/tikv/tikv/pull/6154#issuecomment-562015929
