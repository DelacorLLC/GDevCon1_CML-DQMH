# GDevCon1_CML-DQMH
Repository for CML DQMH demo presented at GDevCon1 and covered in the CLA Summit in Krakow in 2019.
You can find more details here: 
http://delacor.com/how-to-organize-your-large-labview-project-using-libraries/

## Purpose
Show how different reusable modules/libraries can reside in different repositories and still be part of the same project.
The code in one submodule calls code in other submodules. Basically your submodules are your dependencies.
This approach works well if you keep up with the correct revision you want to point to to all your submodules AND
all your submodules are in the same version of LabVIEW.

When making changes to the lower submodules, you can decide if you commit those changes at the calling modules.

## Cloning this repository
When cloning this repository make sure you select to clone recursively, this video shows you how to do it with SourceTree:
https://youtu.be/Lg6Bey-Y2KE
This repository relies in other repositories.

## Code in LabVIEW 2014

## Dependencies
* DQMH 4.2 installed via VIPM
