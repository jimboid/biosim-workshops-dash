# biosim-k8s
A repository containing the cluster configuration for CCPBioSim and HECBioSim resources.

| Container                     | Build Status           | Latest Build   |
| ----------------------------- | ---------------------- | -------------- |
| ccpbiosim base container      | [![ci-1]][ci-link-1]   | [![latest-1]]  |
| uglymol container             | [![ci-22]][ci-link-22] | [![latest-2]]  |
|                               |                        |   |
| aiida lysozyme workshop       | [![ci-2]][ci-link-2]   | [![latest-3]]  |
| aiida gpcr workshop           | [![ci-3]][ci-link-3]   | [![latest-4]]  |
| basic analysis workshop       | [![ci-4]][ci-link-4]   | [![latest-5]]  |
| basic statistics workshop     | [![ci-5]][ci-link-5]   | [![latest-6]]  |
| beginner workshop             | [![ci-6]][ci-link-6]   | [![latest-7]]  |
| clustering workshop           | [![ci-7]][ci-link-7]   | [![latest-8]]  |
| code_entropy workshop         | [![ci-8]][ci-link-8]   | [![latest-9]]  |
| docking workshop              | [![ci-9]][ci-link-9]   | [![latest-10]]  |
| enhanced sampling workshop 1  | [![ci-10]][ci-link-10] | [![latest-11]]  |
| enhanced sampling workshop 2  | [![ci-11]][ci-link-11] | [![latest-12]]  |
| equilibration workshop        | [![ci-12]][ci-link-12] | [![latest-13]]  |
| introamber workshop           | [![ci-13]][ci-link-13] | [![latest-14]]  |
| nemd workshop                 | [![ci-14]][ci-link-14] | [![latest-15]]  |
| openforcefield workshop       | [![ci-15]][ci-link-15] | [![latest-16]]  |
| PCA workshop                  | [![ci-16]][ci-link-16] | [![latest-17]]  |
| pdb2pqr workshop              | [![ci-17]][ci-link-17] | [![latest-18]]  |
| python workshop               | [![ci-18]][ci-link-18] | [![latest-19]]  |
| qmmm workshop                 | [![ci-19]][ci-link-19] | [![latest-20]]  |
| structure validation workshop | [![ci-20]][ci-link-20] | [![latest-21]]  |
| ubiquitin workshop            | [![ci-21]][ci-link-21] | [![latest-22]]  |

[ci-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml
[latest-1]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-jupyterhub-base.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-2]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-2]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml
[latest-2]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-lysozyme-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-3]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-3]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml
[latest-3]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-aiida-gpcr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-4]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-4]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml
[latest-4]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-5]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-5]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml
[latest-5]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-basic-statistics-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-6]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-6]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml
[latest-6]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-beginners-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-7]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-7]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml
[latest-7]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-clustering-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-8]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-8]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml
[latest-8]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-codeentropy-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-9]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-9]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml
[latest-9]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-docking-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-10]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml/badge.svg?branch=main
[ci-link-10]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[latest-10]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part1.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml/badge.svg?branch=main
[ci-link-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml
[latest-11]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-enhanced-sampling-workshop-part2.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-12]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-12]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml
[latest-12]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-equilibration-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-13]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-13]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml
[latest-13]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-introamber-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-14]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-14]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml
[latest-14]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-nemd-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-15]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-15]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml
[latest-15]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-openff-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-16]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-16]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml
[latest-16]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pca-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-17]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-17]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml
[latest-17]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-pdb2pqr-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-18]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-18]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml
[latest-18]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-python-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-19]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-19]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml
[latest-19]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-qmmm-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-20]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-20]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml
[latest-20]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-structure-validation-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-21]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-21]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml
[latest-21]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-ubiquitin-analysis-workshop.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple

[ci-22]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-22]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml
[latest-22]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-uglymol.latest&labelColor=grey&logo=github&logoColor=white&label=latest&color=purple
