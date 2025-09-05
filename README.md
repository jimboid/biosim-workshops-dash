# biosim-k8s
A repository containing the cluster configuration for CCPBioSim and HECBioSim resources.

| Container                     | Build Status           | Latest Build                   |
| ----------------------------- | ---------------------- | ------------------------------ |
| ccpbiosim base container      | [![ci-1]][ci-link-1]   | [![latest-1]][latest-link-1]   |
| uglymol container             | [![ci-2]][ci-link-2]   | [![latest-2]][latest-link-2]   |
|                               |                        |                 |
| aiida lysozyme workshop       | [![ci-3]][ci-link-3]   | [![latest-3]][latest-link-3]   |
| aiida gpcr workshop           | [![ci-4]][ci-link-4]   | [![latest-4]][latest-link-4]   |
| basic analysis workshop       | [![ci-5]][ci-link-5]   | [![latest-5]][latest-link-5]   |
| basic statistics workshop     | [![ci-6]][ci-link-6]   | [![latest-6]][latest-link-6]   |
| beginner workshop             | [![ci-7]][ci-link-7]   | [![latest-7]][latest-link-7]   |
| clustering workshop           | [![ci-8]][ci-link-8]   | [![latest-8]][latest-link-8]   |
| code_entropy workshop         | [![ci-9]][ci-link-9]   | [![latest-9]][latest-link-9]   |
| docking workshop              | [![ci-10]][ci-link-10] | [![latest-10]][latest-link-10]  |
| enhanced sampling workshop 1  | [![ci-11]][ci-link-11] | [![latest-11]][latest-link-11]  |
| enhanced sampling workshop 2  | [![ci-12]][ci-link-12] | [![latest-12]][latest-link-12]  |
| equilibration workshop        | [![ci-13]][ci-link-13] | [![latest-13]][latest-link-13]  |
| introamber workshop           | [![ci-14]][ci-link-14] | [![latest-14]][latest-link-14]  |
| nemd workshop                 | [![ci-15]][ci-link-15] | [![latest-15]][latest-link-15]  |
| openforcefield workshop       | [![ci-16]][ci-link-16] | [![latest-16]][latest-link-16]  |
| PCA workshop                  | [![ci-17]][ci-link-17] | [![latest-17]][latest-link-17]  |
| pdb2pqr workshop              | [![ci-18]][ci-link-18] | [![latest-18]][latest-link-18]  |
| python workshop               | [![ci-19]][ci-link-19] | [![latest-19]][latest-link-19]  |
| qmmm workshop                 | [![ci-20]][ci-link-20] | [![latest-20]][latest-link-20]  |
| structure validation workshop | [![ci-21]][ci-link-21] | [![latest-21]][latest-link-21]  |
| ubiquitin workshop            | [![ci-22]][ci-link-22] | [![latest-22]][latest-link-22]  |

[ci-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml
[latest-1]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-jupyterhub-base.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-jupyterhub-base

[ci-2]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-2]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml
[latest-2]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-uglymol.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-uglymol

[ci-3]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-3]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml
[latest-3]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-lysozyme-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-aiida-lysozyme-workshop

[ci-4]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-4]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml
[latest-4]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-gpcr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-aiida-gpcr-workshop

[ci-5]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-5]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml
[latest-5]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-basic-analysis-workshop

[ci-6]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-6]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml
[latest-6]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-statistics-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-basic-statistics-workshop

[ci-7]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-7]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml
[latest-7]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-beginners-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-beginners-workshop

[ci-8]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-8]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml
[latest-8]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-clustering-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-clustering-workshop

[ci-9]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-9]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml
[latest-9]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-codeentropy-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-codeentropy-workshop

[ci-10]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-10]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml
[latest-10]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-docking-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-docking-workshop

[ci-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml/badge.svg?branch=main
[ci-link-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[latest-11]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part1.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-enhanced-sampling-workshop-part1

[ci-12]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml/badge.svg?branch=main
[ci-link-12]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[latest-12]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part2.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-enhanced-sampling-workshop-part2

[ci-13]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-13]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml
[latest-13]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-equilibration-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-equilibration-workshop

[ci-14]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-14]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml
[latest-14]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-introamber-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-introamber-workshop

[ci-15]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-15]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml
[latest-15]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-nemd-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-nemd-workshop

[ci-16]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-16]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml
[latest-16]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-openff-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-openff-workshop

[ci-17]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-17]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml
[latest-17]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pca-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-pca-workshop

[ci-18]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-18]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml
[latest-18]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pdb2pqr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-pdb2pqr-workshop

[ci-19]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-19]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml
[latest-19]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-python-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-python-workshop

[ci-20]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-20]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml
[latest-20]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-qmmm-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-qmmm-workshop

[ci-21]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-21]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml
[latest-21]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-structure-validation-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-structure-validation-workshop

[ci-22]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-22]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml
[latest-22]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-ubiquitin-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
[latest-link-22]: https://github.com/jimboid/biosim-jupyterhub-base/pkgs/container/biosim-ubiquitin-analysis-workshop
