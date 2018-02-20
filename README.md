# rapl-read-ryzen

Quick and dirty hack to try to use the rapl counters on the AMD Ryzen platform.

At the moment it only reads half the cores as it assumes SMT.

Compile with:

gcc -o ryzen ryzen.c -lm

Needs access to /dev/cpu/CPUNO/msr files. So may need root rights

## Tested on: ##
 * AMD Ryzen Threadripper 1950x
 * AMD Epyc 7501
