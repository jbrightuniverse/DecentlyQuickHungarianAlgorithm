# DecentlyQuickHungarianAlgorithm
A slightly faster implementation of the Hungarian Algorithm in Python.

`alg.py` is a drop-in replacement for the `alg-py` file in [this original version of the Hungarian Algorithm in Python](https://github.com/jbrightuniverse/hungarianalg). For any matrix given to this new version, the algorithm produces a result with the same potentials/weights and optimal revenue sum; however, as the approach to finding the optimal matching is slightly different (a first-come-first-serve approach rather than a check-all approach), the specific matching may be different in matrices that have multiple optimal matchings possible under the same potentials/weights.
