# sequence-counter
Heavily commented, quick script for processing sequence files for length and basepair composition

This is a pure bash script for taking a sequnce file and determining its base content, total length both gapped and ungapped. 
The purpose of the script is to be a portable educational tool for people just learning bash scripting (such as myself)

It's not the best optimized script by any stretch of imagination, but it's simple enough that all its components should be useful for any amateur researcher looking for simple, practical code examples. 

For reference, on a netbook with Celeron N3060 processor and 4GB of ram running Lubuntu 20.04
Human chromosome 1 GRCh38.p13 (about 240.8 MB file) NC_000001.11 takes below time from start to finish.

real    3m46.775s
user    3m23.530s
sys     0m16.992s

Agrobacterium tumefaciens strain GCF_900045375.1 takes below time from start to finish

real    0m5.423s
user    0m4.901s
sys     0m0.467s

I'm working on adding GC percentage display and some other quality of life features to the code. Please let me know if you want to see anything else added.
