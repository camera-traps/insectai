
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Standardising metadata for insect images from camera traps and machine learning output <img src="logo/insectAI.svg" alt="InsectAI Logo" width="300"/>

## Mapping InsectAI datasets to Camtrap DP

This repository is dedicated to testing the [suggested
modifications](https://docs.google.com/document/d/1L6m0Z5kQDzlh2m68XGI1M6btXrI-xApqqgOhlzgxhRY/edit?tab=t.0)
to Camtrap DP by the [InsectAI](https://insect.ai/) community. We aim to
evaluate these changes by mapping datasets to Camtrap DP.

## Repo structure

The repository structure is based on [Cookiecutter Data
Science](http://drivendata.github.io/cookiecutter-data-science/). Files
and directories indicated with `GENERATED` should not be edited
manually.

    ├─ README.md                         : Description of this repository
    ├─ LICENSE                           : Repository license
    ├─ .gitignore                        : Files and directories to be ignored by git
    ├─ src
    │   ├─ insectai_to_camtrapdp.Rmd     : Empty source script to copy
    │   └─ project_name                  : Folder per project
    │       └─ insectai_to_camtrapdp.Rmd : Source script per project
    └─ data
        └─ project_name                  : Folder per project
            ├─ raw                       : Source data, input for mapping script
            ├─ interim                   : Intermediate Camtrap DP - GENERATED
            └─ processed                 : Final Camtrap DP - GENERATED

## How to contribute

This repository is open to contributions from the community. If you have
an insectAI dataset that you would like to map to Camtrap DP, please
follow the guidelines below.

1.  Create a branch for your project.
2.  Create a folder in `src` with the name of your project.
3.  Copy the `insectai_to_camtrapdp.Rmd` file to your project folder.
4.  Create a folder in `data` with the name of your project.
5.  Copy your raw data to the `raw` folder.
6.  Edit the `insectai_to_camtrapdp.Rmd` file to include your
    project-specific code.
7.  Run the `insectai_to_camtrapdp.Rmd` file to generate the Camtrap DP
    files.
8.  Throughout all the previous steps: commit your changes and push to
    your branch. You don’t need to wait to commit until your finished.
9.  Create a pull request to merge your changes into the main branch.

## Relevant sources

- [InsectAI](https://insect.ai/)
- [Camtrap DP - documentation website](https://camtrap-dp.tdwg.org/)
- [Camtrap DP - Github](https://github.com/tdwg/camtrap-dp)
- [InsectAI Metadata standards
  guidelines](https://docs.google.com/document/d/1L6m0Z5kQDzlh2m68XGI1M6btXrI-xApqqgOhlzgxhRY/edit?tab=t.0)
- [InsectAI-demo with example data
  set](https://github.com/cpadubidri/insectAI-demo)
