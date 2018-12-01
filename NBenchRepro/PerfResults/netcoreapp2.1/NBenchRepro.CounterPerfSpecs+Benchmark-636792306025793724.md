# NBenchRepro.CounterPerfSpecs+Benchmark
__Test to ensure that a minimal throughput test can be rapidly executed.__
_12/1/2018 3:10:02 AM_
### System Info
```ini
NBench=NBench.Sys.SysInfo, NBench, Version=1.2.2.0, Culture=neutral, PublicKeyToken=null
OS=Microsoft Windows 10.0.17134 
ProcessorCount=16
CLR=.NET Core 4.6.26515.07,IsMono=False,MaxGcGeneration=2
```

### NBench Settings
```ini
RunMode=Throughput, TestMode=Test
NumberOfIterations=3, MaximumRunTime=00:00:01
Concurrent=False
Tracing=False
```

## Data
-------------------

### Totals
|          Metric |           Units |             Max |         Average |             Min |          StdDev |
|---------------- |---------------- |---------------- |---------------- |---------------- |---------------- |
|[Counter] TestCounter |      operations |   25,439,744.00 |   25,439,744.00 |   25,439,744.00 |            0.00 |

### Per-second Totals
|          Metric |       Units / s |         Max / s |     Average / s |         Min / s |      StdDev / s |
|---------------- |---------------- |---------------- |---------------- |---------------- |---------------- |
|[Counter] TestCounter |      operations |  154,024,468.58 |  153,682,041.30 |  153,301,431.37 |      363,027.74 |

### Raw Data
#### [Counter] TestCounter
|           Run # |      operations |  operations / s | ns / operations |
|---------------- |---------------- |---------------- |---------------- |
|               1 |   25,439,744.00 |  153,301,431.37 |            6.52 |
|               2 |   25,439,744.00 |  153,720,223.96 |            6.51 |
|               3 |   25,439,744.00 |  154,024,468.58 |            6.49 |


## Benchmark Assertions

* [PASS] Expected [Counter] TestCounter to must be greater than 10,000,000.00 operations; actual value was 153,682,041.30 operations.

