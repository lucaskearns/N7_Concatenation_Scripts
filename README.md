# Concat_profile_mut.py

This is a relatively lightweight script to concatenate .mut and .mutga strings from shapemapper output for the purposes of N7 related downstream analysis.

This script is also used to concatenate the N1/3 reactivity profile and N7 reactivity profile output by shapemapper.

## USAGE

python concat_profile_mut.py -m mut output profile

Mut refers to the shared name of the .mut and .mutga (lacking the .mut/ga suffix).
The output refers to what you wish the concatenated script to be named.
Profile refers to the N1/3 reactivity profile lacking the txt extension. Note, the .mut and .mutga files will need to be in the same directory for this to work. 
 
python concat_profile_mut.py -p profile output 

Profile refers to the shared profile prefix of the N1/3 and N7 reactivity profiles and output is the desired output name. The profiles will need to be in the same directory for this to work. 
