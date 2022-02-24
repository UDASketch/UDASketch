# Unbiased Dynamic Adaptive Sketch (UDA)



Source codes of UDA: An unbiased, generic, and accurate sketch for aggregate query in collaborative data stream mining, and four baselines: WavingSketch, Count Sketch, DHS, Cuckoo Counter.

## Descriptions



*single-version*: uda/wavingsketch/countsketch/dhs/cuckoocounter.cpp are single versions of the above five algorithms used for performance comparision.

*distributed-version*: muda/mwavingsketch/mcountsketch/mdhs/mcuckoocounter.cpp are distributed or multiple versions of the above five algorithms used for performace comparision.

*WavingSketch*/*DHS*/*CuckooCounter*: these directories are original codes open-sourced by their authors. 

Each algorithm can be built and run by the following command: 

```
g++ -std=c++11 *.cpp -O3 -o *
./*
```
