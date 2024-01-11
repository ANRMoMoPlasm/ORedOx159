# ORedOx159
The ORedOx159 database is a chemical dataset containing 159 reduction and oxidization potentials of 159 organic molecules.

The archive contains 477 structures fully optimized at DFT level (i.e., PBE0/def2-TZVPP) and their respective SCF and Gibbs free energies. It counts
- 159 ground-state structures: file name *_gn.xyz
- 159 oxidized structures: file name *_ox.xyz
- 159 reduced structures: file name *_rd.xyz

The name of each xyz file (i.e., xx-yy_aa_bb.xyz) is decomposed such as:
- xx: family name
- yy: number of the system within the family
- aa: charge of the system: {0n: 0, 1a: -1, 2a: -2, 1c: +1, 2c: +2}
- bb: ground-state (gn), oxidized (ox) or reduced (rd) structure

# Benchmark
A benchmark comparison at various DFT levels is provided so as to evaluate the impact of the exchange-correlation approximation on the computed SCF and Gibbs free energies.
