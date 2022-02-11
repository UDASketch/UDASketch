# Unbiased Dynamic Adaptive Sketch (UDA)

---

Source codes of UDA: An unbiased, generic, and accurate sketch for aggregate query in collaborative data stream mining, and four baselines: WavingSketch, Count Sketch, DHS, Cuckoo Counter.

## Descriptions

---

uda/wavingsketch/countsketch/dhs/cuckoocounter.cpp are single versions of the above five algorithms;
muda/mwavingsketch/mcountsketch/mdhs/mcuckoocounter.cpp are distributed or multiple versions of the above five algorithms.

Each algorithm can be built and run by the following command: 

```
g++ -std=c++11 *.cpp -O3 -o *
./*
```
