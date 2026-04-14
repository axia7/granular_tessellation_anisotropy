All tessellations have N = 12.

"tess_pressure" contains the 5 pressure values that all tessellation elastic tensors are measured at.

"homog_tess_cmat" contains elastic tensors for 600 different homogeneous tessellated materials. The elastic tensors are measured at 5 different pressures. The reshaped array has size (600x5x6x6).

"homog_tess_cmat_single" contains elastic tensors for the corresponding granular packings within single voxels (non-tessellated). The elastic tensors are measured at 5 different pressures. The reshaped array has size (600x5x6x6).

"heterog_tess_cmat" contains elastic tensors for 848 different heterogeneous (2 different configurations) tessellated materials. The elastic tensors are measured at 5 different pressures. The reshaped array has size (848x5x6x6).

"heterog_tess_cmat_single1" contains elastic tensors for configuration 1 within a single voxel (non-tessellated). The elastic tensors are measured at 5 different pressures. The reshaped array has size (848x5x6x6).

"heterog_tess_cmat_single2" contains elastic tensors for configuration 2 within a single voxel (non-tessellated). The elastic tensors are measured at 5 different pressures. The reshaped array has size (848x5x6x6).

"flex_tess_cmat" contains elastic tensors for 600 different homogeneous tessellated materials with 6 randomly relaxed exterior vertices (10 random seeds to generate relaxed vertices). The elastic tensors are measured at 5 different pressures. The reshaped array has size (10x600x5x6x6). The indices are over vertex relaxation seed, configuration, and pressure respectively.

"flex_tess_cmat_single" contains elastic tensors for the corresponding single voxels (non-tessellated). The elastic tensors are measured at 5 different pressures. The reshaped array has size (10x600x5x6x6).
