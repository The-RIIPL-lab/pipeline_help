================
nifti/ Directory
================

Nifti Image Files Directory
---------------------------

Located : /nitfi/

This the default output location of the :doc:`dcm2niix` process.

Example Structure
-----------------
| ├── BRPYT153-0001-001-0001-0003-fl2d1.dicom
| ├── BRPYT153-0001-001-0001-0003-fl2d1.info
| ├── BRPYT153-0001-001-0001-0003-fl2d1.nii
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.dicom
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.info
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.nii
| ├── BRPYT153-0003-190-0001-6650-epfid2d161.dicom
| ├── BRPYT153-0003-190-0001-6650-epfid2d161.info
| ...
| ├── BRPYT153-0032-003-0001-0240-epb300t.bval
| ├── BRPYT153-0032-003-0001-0240-epb300t.bvec
| ├── BRPYT153-0032-003-0001-0240-epb300t.dicom
| ├── BRPYT153-0032-003-0001-0240-epb300t.info
| ├── BRPYT153-0032-003-0001-0240-epb300t.nii
| ├── cat12 ( :doc:`cat12`)
| └── jpegs ( :doc:`jpeg`)

File Identification
-------------------
* .dicom files - A 3D dicom file for storing the dicom header information 
* .info files - A list of select dicom header info in plain text
* .json files - JSON formatted outputs of the dicom header created by :doc:`dcm2niix`
* .nii files - Nifti Image files created by :doc:`dcm2niix`
* .bval files - b-value data text files. Needed for :doc:`dti_pipeline`.
* .bvec files - b-vector data text files. Needed for :doc:`dti_pipeline`.