# DSC Fetal Brain MRI Reconstruction Pipeline

This is an open-source [_ChRIS_](https://chrisproject.org) pipeline for multiple stack to single volume
fetal brain MRI reconstruction. It has been tested on Siemens HASTE T2 _in-utero_ data.

The pipeline is comprised of several machine-learning steps and requires a GPU.
The final step of reconstruction is [_NeSVoR_](https://github.com/daviddmc/NeSVoR/)
(however, this pipeline uses different programs for brain masking and quality assessment than
the _NeSVoR_ pipeline).

Brain masking and quality assessment steps are software produced by Kiho Im's students,
Sofia Urosa and Iván Legorreta.

https://research.childrenshospital.org/neuroim/fetal-brain-mri-pipeline

## See Also

Similar fetal brain reconstruction pipeline methodologies are described in https://doi.org/10.1259/bjr.20220071
