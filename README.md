# Unbiased Dynamic Adaptive Sketch (UDA)

---

Source codes of UDA: An unbiased, generic, and accurate sketch for aggregate query in collaborative data stream mining, and four baselines: WavingSketch, Count Sketch, DHS, Cuckoo Counter.

## Descriptions

---

The directory "single" contains single versions of the above five algorithms;
The directory "distributed" contains distributed or multiple versions of the above five algorithms.

Each algorithm can be built and run by the following command: 

```
g++ -std=c++11 *.cpp -O3 -o *
./*
```