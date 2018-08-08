## Resubmission
Submission failed CRAN pretests because rth was used as a role
in the DESCRIPTION file.  I removed this role and the only
note in the revised package is the new submission note.

## Test environments
* local Windows 7 Professional development and install, R 3.5.1
* local 0S X install, R 3.5.0
* local ubuntu 16.04 install, R 3.5.0
* devtools::build_win()

Packaged developed on Windows machine, built using devtools::build().

## R CMD check results (when ran using devtools::check())
0 errors | 0 warnings | 0 notes

## Results from running devtools::build_win()
Two notes:  
1) One indicates this is a new submission
2) The second note is a blank note under, "checking DESCRIPTION meta-information ..."
   The cause of this note is my use of "rth" as a role for Diane Catellier who
   funded this package development and managed the project.

## Downstream dependencies
BayesCTDesign is a new package.

## Issues related to select Cran Policies
Email of maintainer: beggleston@rti.org

I have installed the package locally and tested the package 
on Windows, Mac, and Ubuntu 16.04 linux machines.