``` ini

BenchmarkDotNet=v0.11.0, OS=Windows 10.0.17134.228 (1803/April2018Update/Redstone4), VM=Hyper-V
Intel Xeon CPU E5-2620 0 2.00GHz, 1 CPU, 3 logical and 3 physical cores
.NET Core SDK=2.1.301
  [Host]     : .NET Core 2.1.1 (CoreCLR 4.6.26606.02, CoreFX 4.6.26606.05), 64bit RyuJIT  [AttachedDebugger]
  DefaultJob : .NET Core 2.1.1 (CoreCLR 4.6.26606.02, CoreFX 4.6.26606.05), 64bit RyuJIT


```
|           Method |     Mean |     Error |    StdDev |   Median |
|----------------- |---------:|----------:|----------:|---------:|
| InvokeController | 4.308 ms | 0.3350 ms | 0.9666 ms | 4.697 ms |
