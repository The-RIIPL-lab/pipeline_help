NODDI Output
============

NODDI Output ¶ 
 
 Located : /NODDI 
 
 NODDI
├── FieldMapCorrection
└── run1
    └── AMICO
        └── NODDI
 
 
 Neurite Orientation Dispersion and Density Imaging (NODDI)  output data. 
 Primary Output Files: 
 
 _ECC.nii - eddy-current corrected EPI image 
 -NODDI_ICVF.nii - Native Intracellular volume fraction 
 -NODDI_ISOVF.nii - Native Isotropic Volume Fraction 
 -NODDI_OD.nii - Native orientation dispersion index 
 dti_bvals.txt - DTI bvals 
 dti_bvecs.txt - DTI bvecs 
 FieldMapCorrection - directory used for TOPUP correction 
 
 
 Tip 
 NODDI outputs are normalized to MNI template using the CAT12 transforms. These smoothed and normalized files can be found in nifti/cat12/NODDI 
 
 For more information: 
 
 The AMICO NODDI github repo:  https://github.com/daducci/AMICO 
 More info on the “orientation dispersion index”:  https://www.sciencedirect.com/science/article/pii/S1053811912003539

