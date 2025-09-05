# biosim-k8s
A repository containing the cluster configuration for CCPBioSim and HECBioSim resources.

| Container Source                       | Build Status       | Latest Build          |
| -------------------------------------- | ------------------ | --------------------- |
| [ccpbiosim base container][ln-1]       | [![ci-1]][cil-1]   | [![lat-1]][latl-1]    |
| [uglymol container]][ln-2]             | [![ci-2]][cil-2]   | [![lat-2]][latl-2]    |
|                                        |                    |                       |
| [aiida lysozyme workshop][ln-3]        | [![ci-3]][cil-3]   | [![lat-3]][latl-3]    |
| [aiida gpcr workshop][ln-4]            | [![ci-4]][cil-4]   | [![lat-4]][latl-4]    |
| [basic analysis workshop][ln-5]        | [![ci-5]][cil-5]   | [![lat-5]][latl-5]    |
| [basic statistics workshop][ln-6]      | [![ci-6]][cil-6]   | [![lat-6]][latl-6]    |
| [beginner workshop][ln-7]              | [![ci-7]][cil-7]   | [![lat-7]][latl-7]    |
| [clustering workshop][ln-8]            | [![ci-8]][cil-8]   | [![lat-8]][latl-8]    |
| [code_entropy workshop][ln-9]          | [![ci-9]][cil-9]   | [![lat-9]][latl-9]    |
| [docking workshop][ln-10]              | [![ci-10]][cil-10] | [![lat-10]][latl-10]  |
| [enhanced sampling workshop 1][ln-11]  | [![ci-11]][cil-11] | [![lat-11]][latl-11]  |
| [enhanced sampling workshop 2][ln-12]  | [![ci-12]][cil-12] | [![lat-12]][latl-12]  |
| [equilibration workshop][ln-13]        | [![ci-13]][cil-13] | [![lat-13]][latl-13]  |
| [introamber workshop][ln-14]           | [![ci-14]][cil-14] | [![lat-14]][latl-14]  |
| [nemd workshop][ln-15]                 | [![ci-15]][cil-15] | [![lat-15]][latl-15]  |
| [openforcefield workshop][ln-16]       | [![ci-16]][cil-16] | [![lat-16]][latl-16]  |
| [PCA workshop][ln-17]                  | [![ci-17]][cil-17] | [![lat-17]][latl-17]  |
| [pdb2pqr workshop][ln-18]              | [![ci-18]][cil-18] | [![lat-18]][latl-18]  |
| [python workshop][ln-19]               | [![ci-19]][cil-19] | [![lat-19]][latl-19]  |
| [qmmm workshop][ln-20]                 | [![ci-20]][cil-20] | [![lat-20]][latl-20]  |
| [structure validation workshop][ln-21] | [![ci-21]][cil-21] | [![lat-21]][latl-21]  |
| [ubiquitin workshop][ln-22]            | [![ci-22]][cil-22] | [![lat-22]][latl-22]  |

[ln-1]: https://github.com/jimboid/biosim-jupyterhub-base
[ci-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml/badge.svg?branch=main
[cil-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml
[lat-1]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-jupyterhub-base.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-jupyterhub-base

[ln-1]: https://github.com/jimboid/biosim-uglymol
[ci-2]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml/badge.svg?branch=main
[cil-2]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml
[lat-2]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-uglymol.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-2]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-uglymol

[ln-1]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop
[ci-3]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-3]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml
[lat-3]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-lysozyme-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-3]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-aiida-lysozyme-workshop

[ln-1]: https://github.com/jimboid/biosim-aiida-gpcr-workshop
[ci-4]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-4]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml
[lat-4]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-gpcr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-4]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-aiida-gpcr-workshop

[ln-1]: https://github.com/jimboid/biosim-basic-analysis-workshop
[ci-5]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-5]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml
[lat-5]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-5]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-basic-analysis-workshop

[ln-1]: https://github.com/jimboid/biosim-basic-statistics-workshop
[ci-6]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-6]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml
[lat-6]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-statistics-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-6]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-basic-statistics-workshop

[ln-1]: https://github.com/jimboid/biosim-beginners-workshop
[ci-7]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-7]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml
[lat-7]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-beginners-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-7]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-beginners-workshop

[ln-1]: https://github.com/jimboid/biosim-clustering-workshop
[ci-8]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-8]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml
[lat-8]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-clustering-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-8]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-clustering-workshop

[ln-1]: https://github.com/jimboid/biosim-codeentropy-workshop
[ci-9]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-9]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml
[lat-9]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-codeentropy-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-9]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-codeentropy-workshop

[ln-1]: https://github.com/jimboid/biosim-docking-workshop
[ci-10]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-10]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml
[lat-10]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-docking-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-10]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-docking-workshop

[ln-1]: https://github.com/jimboid/biosim-enhanced-sampling-workshop
[ci-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml/badge.svg?branch=main
[cil-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[lat-11]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part1.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-11]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-enhanced-sampling-workshop-part1

[ln-1]: https://github.com/jimboid/biosim-enhanced-sampling-workshop
[ci-12]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml/badge.svg?branch=main
[cil-12]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[lat-12]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part2.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-12]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-enhanced-sampling-workshop-part2

[ln-1]: https://github.com/jimboid/biosim-equilibration-workshop
[ci-13]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-13]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml
[lat-13]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-equilibration-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-13]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-equilibration-workshop

[ln-1]: https://github.com/jimboid/biosim-introamber-workshop
[ci-14]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-14]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml
[lat-14]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-introamber-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-14]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-introamber-workshop

[ln-1]: https://github.com/jimboid/biosim-nemd-workshop
[ci-15]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-15]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml
[lat-15]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-nemd-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-15]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-nemd-workshop

[ln-1]: https://github.com/jimboid/biosim-openff-workshop
[ci-16]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-16]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml
[lat-16]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-openff-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-16]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-openff-workshop

[ln-1]: https://github.com/jimboid/biosim-pca-workshop
[ci-17]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-17]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml
[lat-17]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pca-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-17]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-pca-workshop

[ln-1]: https://github.com/jimboid/biosim-pdb2pqr-workshop
[ci-18]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-18]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml
[lat-18]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pdb2pqr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-18]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-pdb2pqr-workshop

[ln-1]: https://github.com/jimboid/biosim-python-workshop
[ci-19]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-19]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml
[lat-19]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-python-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-19]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-python-workshop

[ln-1]: https://github.com/jimboid/biosim-qmmm-workshop
[ci-20]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-20]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml
[lat-20]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-qmmm-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-20]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-qmmm-workshop

[ln-1]: https://github.com/jimboid/biosim-structure-validation-workshop
[ci-21]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-21]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml
[lat-21]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-structure-validation-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-21]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-structure-validation-workshop

[ln-1]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop
[ci-22]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[cil-22]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml
[lat-22]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-ubiquitin-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latl-22]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-ubiquitin-analysis-workshop
