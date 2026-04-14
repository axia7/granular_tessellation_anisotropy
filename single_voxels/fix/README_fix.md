"fix_vox_press" contains the 20 pressure values that the elastic tensors are measured at.

"n_list_fix" contains the 5 values of N that the elastic tensors are measured for

"cubic_fix_vox_cmat" contains 100 elastic tensors as a function of N and p for the fix cubic boundary condition. The reshaped array size is 5x100x20x6x6 (indexing system size, configuration, and pressure respectively)

Similarly, "rhomb_fix_vox_cmat" contains 100 elastic tensors generated in the fix rhombohedral boundary condition and "triclinic_fix_vox_cmat" contains 100 elastic tensors generated in the fix triclinic boundary condition 
