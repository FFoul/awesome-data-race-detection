# Awesome Data Race Detection
A list of awesome researchers and papers about data race detecton.

- [Awesome Data Race Detection](#awesome-data-race-detection)
- [Papers](#papers)
  - [Static](#static)
  - [Dynamic](#dynamic)
  - [Hybird](#hybird)
  - [Alias Analysis](#alias-analysis)
- [Industrial Practices](#industrial-practices)
- [Contribute](#contribute)


# Papers
## Static
| Year | Conf.           | Paper                                                                                                                                           | Code                                             |
|------|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------|
| 2003 | SIGOPS          | [RacerX: Effective, static detection of race conditions and deadlocks](https://dl.acm.org/doi/abs/10.1145/1165389.945468)                       |                                                  |
| 2006 | SIGPLAN Notice  | [LOCKSMITH: context-sensitive correlation analysis for race detection](https://dl.acm.org/doi/abs/10.1145/1133255.1134019)                      | [link](https://github.com/polyvios/locksmith/)   |
| 2007 | FSE             | [RELAY: static race detection on millions of lines of code](https://dl.acm.org/doi/abs/10.1145/1287624.1287654)                                 | [link](https://github.com/vesalvojdani/relay-sv) |
| 2008 | SIGPLAN Notice  | [Dataflow analysis for concurrent programs using datarace detection](https://dl.acm.org/doi/abs/10.1145/1375581.1375620)                        |                                                  |
| 2018 | OOPSLA          | [RacerD: compositional static race detection](https://dl.acm.org/doi/abs/10.1145/3276514)                                                       | [link](https://github.com/facebook/infer.git)    |
| 2019 | S&P             | [Razzer: Finding Kernel Race Bugs through Fuzzing](https://ieeexplore.ieee.org/abstract/document/8835326)                                       |                                                  |
| 2024 | USENIX Security | [LR-Miner: Static Race Detection in OS Kernels by Mining Locking Rules](https://www.usenix.org/conference/usenixsecurity24/presentation/li-tuo) |                                                  |


## Dynamic
| Year | Conf.   | Paper                                                                                                                           | Code |
|------|---------|---------------------------------------------------------------------------------------------------------------------------------|------|
| 1997 | TOCS    | [Eraser: A Dynamic Data Race Detector for Multithreaded Programs](https://dl.acm.org/doi/10.1145/265924.265927)                 |      | 
| 2007 | PLDI    | [Automatically Classifying Benign and Harmful Data Races Using Replay Analysis](https://dl.acm.org/doi/10.1145/1250734.1250738) |      |
| 2010 | OSDI    | [Effective Data-Race Detection for the Kernel](https://www.usenix.org/conference/osdi10/effective-data-race-detection-kernel)   |      |
| 2019 | Eurosys | [Lockdoc: Trace-based analysis of locking in the linux kernel](https://dl.acm.org/doi/abs/10.1145/3302424.3303948)              |      |

## Hybird

| Year | Conf. | Paper                                                                                       | Code |
|------|-------|---------------------------------------------------------------------------------------------|------|
| 2013 | SOSP  | [RaceMob: Crowdsourced Data Race Detection](https://dl.acm.org/doi/10.1145/2517349.2522736) |      |




## Alias Analysis

| Year | Conf.           | Paper                                                                                                                                                                       | Code |
|------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| 2023 | USENIX Security | [A Hybrid Alias Analysis and Its Application to Global Variable Protection in the  Linux Kernel](https://www.usenix.org/conference/usenixsecurity23/presentation/li-guoren) |      |


    

# Industrial Practices

- [Google Threadsanitizer](https://github.com/google/sanitizers/wiki/threadsanitizercppmanual)
- 
---
# Contribute
This is an active repository and your contributions are always welcome! Do not hesitate to create pull requests.
