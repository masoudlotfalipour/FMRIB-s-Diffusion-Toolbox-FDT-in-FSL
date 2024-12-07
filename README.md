# Diffusion MRI Processing and Analysis Pipeline
This repository contains a comprehensive workflow for preprocessing, correcting, and analyzing diffusion MRI (dMRI) data using FMRIB's Diffusion Toolbox (FDT) in FSL. The pipeline includes steps for distortion correction, motion correction, tensor fitting, and tract-based spatial statistics (TBSS), along with region-specific analyses of fractional anisotropy (FA) values.

# File Structure
├── dwi/
│   ├── sub-CON02_ses-preop_acq-AP_dwi.nii.gz   # Diffusion MRI data (AP)
│   ├── sub-CON02_ses-preop_acq-PA_dwi.nii.gz   # Diffusion MRI data (PA)
│   ├── sub-CON02_ses-preop_acq-AP_dwi.bval     # b-values
│   ├── sub-CON02_ses-preop_acq-AP_dwi.bvec     # b-vectors
│   ├── acq_param.txt                           # Acquisition parameters
│   ├── AP_PA_topup_*                           # Topup results
│   ├── AP_eddy_unwarped_*                      # Eddy results
│   ├── dti_FA.nii.gz                           # Fractional anisotropy map
│   └── tbss/                                   # TBSS results
