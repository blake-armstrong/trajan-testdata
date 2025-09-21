# trajan-testdata

## input
i00000000 : PDB file. Cubic. PBC. Approximately 50 Angstroms. 4092 water molecules. 
i00000001 : Same as 00000000 with additional Ca - CO3 close contact ion pair.
i00000002 : DCD file containing 11 frames from a simulation starting at 00000000.

## output
o00000000 : RDF output for O - O using GPTA over the i00000000 + i00000002 input files.
