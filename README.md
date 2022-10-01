# KiCAD_QACheck
This repository contains a PULL_REQUEST_TEMPLATE.md file that should be used in all repositories with PCB Designs.

# Usage

In order to add this to a new github repository, run:

`git submodule add git@github.com:lhr-solar/KiCAD_QAC.git`

`cp KiCAD_QAC/PULL_REQUEST_TEMPLATE.md .`

All PULL_REQUEST_TEMPLATE files should be either inside the repository, or inside a directory with the same name. Since this repository also contains a README.md file, we need to add a branch that doesn't contain this file and only contains the PR Template file. The above command adds the submodule to the folder `.github/PULL_REQUEST_TEMPLATE` and has it follow the `Production` branch which will have the README file removed.
