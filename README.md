# rapl-read-ryzen

Quick and dirty hack to try to use the rapl counters on the AMD Ryzen platform.

Compile with:

gcc -o ryzen ryzen.c -lm

Needs access to /dev/cpu/CPUNO/msr files. So may need root rights

## Tested on: ##
 * AMD Ryzen Threadripper 1950x
