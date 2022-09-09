# MYSTRAN_Benchmark
Benchmarks for MYSTRAN

MYSTRAN_Benchmark is intended to:
 - Compare results between versions of MYSTRAN
   - Find/avoid regressions in the software (it worked in version 10.0, but not 11.0)
 - Compare results for models that are correcct/assumed to be correct.  If results are nonsense, it's a bad example.
   - If a 2 node spring element (CELAS1) with a stiffness of 1.0 results and force of 1.0 results
     in a defelection of 100000.0 (F=Kx), there's no point in verifying the example has the same answer across versions.  Instead, it should be flagged as a bug.

This repo is not intended to be used:
 - performance testing.
