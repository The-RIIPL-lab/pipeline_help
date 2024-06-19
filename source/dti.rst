==========
DTI/ Directory
==========

Diffusion Tensor Imaging Native Processing Outputs
 
Located : /DTI 
 
Example Structure
-----------------
 
| ├── camino
| ├── dti_bvals.txt
| ├── dti_bvecs.txt
| ├── dtitk
| ├── FieldMapCorrection
| ├── HFS070POST20171220-0004-001-0001-0192-tfl3d116ns.dicom
| ├── HFS070POST20171220-0004-001-0001-0192-tfl3d116ns.info
| ├── HFS070POST20171220-0004-001-0001-0192-tfl3d116ns.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_FA.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_L1.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_L2.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_L3.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_MD.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC_MO.nii
| ├── HFS070POST20171220-0024-031-0001-1860-epb0_ECC.nii
| ...
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_FA.nii.gz
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_L1.nii.gz
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_L2.nii.gz
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_L3.nii.gz
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_MD.nii.gz
| ├── swrHFS070POST20171220-0024-031-0001-1860-epb0_ECC_S0.nii.gz


File Identification
-------------------
* _ECC.nii - eddy-current corrected EPI image 
* _ECC_FA.nii - eddy-current corrected fractional anisotropy map 
* _ECC_L1.nii - eddy-current corrected principal diffusivity (L1) 
* _ECC_L2.nii - eddy-current corrected principal diffusivity (L2) 
* _ECC_L3.nii - eddy-current corrected principal diffusivity (L3) 
* _ECC_MD.nii - eddy-current corrected mean diffusivity map 
* _ECC_V1.nii - eddy-current corrected orthogonal vectors (V1) 
* _ECC_V2.nii - eddy-current corrected orthogonal vectors (V2) 
* _ECC_V3.nii - eddy-current corrected orthogonal vectors (V3) 
* p[0-3]*-tfl3d116ns.nii - SPM12 tissue segmentations from T1w image (native spaced) 
* rp[0-3]*tfl3d116ns.nii - resampled SPM12 tissue segmentations from T1w image (to native DTI resolution) 
* w3*_ECC_FA.nii - SPM12 eddy-current corrected fractional anisotropy map warped to template (normalized) 
* swr*_ECC_FA.nii.gz - SPM12 smoothed, warped, eddy-current corrected FA map (available for most DTI measures) 
* y_*_ECC_S0.nii - forward SPM12 transform file from native to template 
* dti_bvals.txt - DTI bvals 
* dti_bvecs.txt - DTI bvecs 
* FieldMapCorrection - directory used for TOPUP correction 

.. For additional information, contact our specialist: Dr. Jeongchul Kim