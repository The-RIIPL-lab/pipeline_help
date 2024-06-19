================
cat12/ Directory
================

CAT12 Tissue Segmentation and Normalization Output
--------------------------------------------------

Located : /nitfi/cat12 

Output location for the :doc:`cat_segmentation` workflow.

Example Structure
-----------------
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns_bet_mask.nii.gz
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns_bet.nii.gz
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.dicom
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.info
| ├── BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ...
| ├── wmBRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ├── wmiBRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ├── wp0BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ├── wp1BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ├── wp2BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| ├── wp3BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz
| └── y_BRPYT153-0002-001-0001-0192-tfl3d116ns.nii.gz

File Identification
-------------------
* `cat_*.mat`` and `cat_*.xml` - formatted report data from the CAT12 process
* `catreport*.pdf` - PDF formatted report data
* `iy_*-tfl3d116ns.nii.gz` - Inverse Transform
* `y_*-tfl3d116ns.nii.gz` - Transform 