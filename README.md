<<<<<<< HEAD
# ZM Kinetic Energy Parcel Calculation
## Summary
This branch includes the estimate of the parcel kinetic energy in the Zhang-McFarlane deep convection for the calculation of the entraining buoyancy profile which determines the intergrated CAPE. The convection top is no longer determined by the top most negative buyancy regions (depending on the value zmconv_num_cin (=1 in CAM6, =5 in CAM5). It is determined by the KE=0 level. KE is dtermined by the transfer of energy from the buoyancy PE, with a sepcific efficiency and initial parcel KE.
||||||| 8554477a
# CAM: The Community Atmosphere Model

## NOTE: This is **unsupported** development code and is subject to the [CESM developer's agreement](http://www.cgd.ucar.edu/cseg/development-code.html).

### CAM Documentation - https://ncar.github.io/CAM/doc/build/html/index.html

### CAM6 namelist settings - http://www.cesm.ucar.edu/models/cesm2/settings/current/cam_nml.html

Please see the [wiki](https://github.com/ESCOMP/CAM/wiki) for complete documentation on CAM, getting started with git and how to contribute to CAM's development.
=======
# CAM: The Community Atmosphere Model

## NOTE: This is **unsupported** development code and is subject to the [CESM developer's agreement](http://www.cgd.ucar.edu/cseg/development-code.html).

-----------

To checkout externals:
    bin/git-fleximod update

The externals are stored in:
    .gitmodules

.gitmodules can be modified.  Then run "bin/git-fleximod update" to get the updated externals

Details about git-fleximod and the variables in the .gitmodules file can be found at:  .lib/git-fleximod/README.md

------------

### CAM Documentation - https://ncar.github.io/CAM/doc/build/html/index.html

### CAM6 namelist settings - http://www.cesm.ucar.edu/models/cesm2/settings/current/cam_nml.html

Please see the [wiki](https://github.com/ESCOMP/CAM/wiki) for complete documentation on CAM, getting started with git and how to contribute to CAM's development.
>>>>>>> tags/cam6_4_032
