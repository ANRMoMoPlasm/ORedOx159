# ORedOx159
The ORedOx159 database is a chemical dataset containing 159 reduction and oxydation potentials of 159 organic molecules.

The archive contains 477 structures fully optimized at DFT level (i.e., PBE0/def2-SVP) and their respective SCF and Gibbs free energies. It counts
- 159 ground-state structures: file name *_gn.xyz
- 159 oxydized structures: file name *_ox.xyz
- 159 reduced structures: file name *_rd.xyz

The name of each xyz file (i.e., xx-yy_aa_bb.xyz) is decomposed such as:
- xx: familly name
- yy: number of the system within the familly
- aa: charge of the system: {0n: 0, 1a: -1, 2a: -2, 1c: +1, 2c: +2}
- bb: ground-state (gn), oxydized (ox) or reduced (rd) structure
