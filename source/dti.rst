DTI output
==========

DTI output ¶ 
 
 Located : /DTI 
 
 DTI
├── camino
├── dtitk
├── FieldMapCorrection
└── tbss
 
 
 Diffusion Tensor Imaging (DTI)  directories 
 Primary Output Files: 
 
 _ECC.nii - eddy-current corrected EPI image 
 _ECC_FA.nii - eddy-current corrected fractional anisotropy map 
 _ECC_L1.nii - eddy-current corrected principal diffusivity (L1) 
 _ECC_L2.nii - eddy-current corrected principal diffusivity (L2) 
 _ECC_L3.nii - eddy-current corrected principal diffusivity (L3) 
 _ECC_MD.nii - eddy-current corrected mean diffusivity map 
 _ECC_M0.nii - 
 _ECC_S0.nii - 
 _ECC_V1.nii - eddy-current corrected orthogonal vectors (V1) 
 _ECC_V2.nii - eddy-current corrected orthogonal vectors (V2) 
 _ECC_V3.nii - eddy-current corrected orthogonal vectors (V3) 
 p[0-3]*-tfl3d116ns.nii - SPM12 tissue segmentations from T1w image (native spaced) 
 rp[0-3]*tfl3d116ns.nii - resampled SPM12 tissue segmentations from T1w image (to native DTI resolution) 
 w3*_ECC_FA.nii - SPM12 eddy-current corrected fractional anisotropy map warped to template (normalized) 
 swr*_ECC_FA.nii.gz - SPM12 smoothed, warped, eddy-current corrected FA map (available for most DTI measures) 
 y_*_ECC_S0.nii - forward SPM12 transform file from native to template 
 dti_bvals.txt - DTI bvals 
 dti_bvecs.txt - DTI bvecs 
 FieldMapCorrection - directory used for TOPUP correction 
 
 
 Tip 
 DTI outputs are normalized to MNI template using the CAT12 transforms. These smoothed and normalized files can be found in nifti/cat12/DTI 
 
 For more information, contact: 
 
 Dr. Jeongchul Kim

