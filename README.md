# afni_scripts
Scripts for afni pre-proc and analysis

# create_roi.sh
    Create a spherical volume.
    argv[1] = X coordinates
    argv[2] = Y coordinates
    argv[3] = Z coordinates
    argv[4] = ROI name
    argv[5] = volume in mm^3
    argv[6] = template to be used
    
Example: ./create_roi.sh 48 -63 21 R-BA39 9 MNI_EPI+tlrc
