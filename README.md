# biosim-k8s
A repository containing the cluster configuration for CCPBioSim and HECBioSim resources.

| Container                     | Build Status           | Latest Build  |
| ----------------------------- | ---------------------- | ------------- |
| ccpbiosim base container      | [![ci-1]][ci-link-1]   | [![latest-1]] |
| uglymol container             | [![ci-22]][ci-link-22] |
|                               |                        |
| aiida lysozyme workshop       | [![ci-2]][ci-link-2]   |
| aiida gpcr workshop           | [![ci-3]][ci-link-3]   |
| basic analysis workshop       | [![ci-4]][ci-link-4]   |
| basic statistics workshop     | [![ci-5]][ci-link-5]   |
| beginner workshop             | [![ci-6]][ci-link-6]   |
| clustering workshop           | [![ci-7]][ci-link-7]   |
| code_entropy workshop         | [![ci-8]][ci-link-8]   |
| docking workshop              | [![ci-9]][ci-link-9]   |
| enhanced sampling workshop 1  | [![ci-10]][ci-link-10] |
| enhanced sampling workshop 2  | [![ci-11]][ci-link-11] |
| equilibration workshop        | [![ci-12]][ci-link-12] |
| introamber workshop           | [![ci-13]][ci-link-13] |
| nemd workshop                 | [![ci-14]][ci-link-14] |
| openforcefield workshop       | [![ci-15]][ci-link-15] |
| PCA workshop                  | [![ci-16]][ci-link-16] |
| pdb2pqr workshop              | [![ci-17]][ci-link-17] |
| python workshop               | [![ci-18]][ci-link-18] |
| qmmm workshop                 | [![ci-19]][ci-link-19] |
| structure validation workshop | [![ci-20]][ci-link-20] |
| ubiquitin workshop            | [![ci-21]][ci-link-21] |

[ci-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-1]: https://github.com/jimboid/biosim-jupyterhub-base/actions/workflows/build.yaml
[latest-1]: https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fjimboid.github.io%2Fbiosim-workshops-dash%2Fworkshop.json&query=%24.containers.biosim-jupyterhub-base.latest&logo=github&logoColor=grey&label=latest&color=purple

[ci-2]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-2]: https://github.com/jimboid/biosim-aiida-lysozyme-workshop/actions/workflows/build.yaml

[ci-3]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-3]: https://github.com/jimboid/biosim-aiida-gpcr-workshop/actions/workflows/build.yaml

[ci-4]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-4]: https://github.com/jimboid/biosim-basic-analysis-workshop/actions/workflows/build.yaml

[ci-5]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-5]: https://github.com/jimboid/biosim-basic-statistics-workshop/actions/workflows/build.yaml

[ci-6]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-6]: https://github.com/jimboid/biosim-beginners-workshop/actions/workflows/build.yaml

[ci-7]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-7]: https://github.com/jimboid/biosim-clustering-workshop/actions/workflows/build.yaml

[ci-8]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-8]: https://github.com/jimboid/biosim-codeentropy-workshop/actions/workflows/build.yaml

[ci-9]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-9]: https://github.com/jimboid/biosim-docking-workshop/actions/workflows/build.yaml

[ci-10]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container1.yaml/badge.svg?branch=main
[ci-link-10]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml

[ci-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build-container2.yaml/badge.svg?branch=main
[ci-link-11]: https://github.com/jimboid/biosim-enhanced-sampling-workshop/actions/workflows/build.yaml

[ci-12]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-12]: https://github.com/jimboid/biosim-equilibration-workshop/actions/workflows/build.yaml

[ci-13]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-13]: https://github.com/jimboid/biosim-introamber-workshop/actions/workflows/build.yaml

[ci-14]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-14]: https://github.com/jimboid/biosim-nemd-workshop/actions/workflows/build.yaml

[ci-15]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-15]: https://github.com/jimboid/biosim-openff-workshop/actions/workflows/build.yaml

[ci-16]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-16]: https://github.com/jimboid/biosim-pca-workshop/actions/workflows/build.yaml

[ci-17]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-17]: https://github.com/jimboid/biosim-pdb2pqr-workshop/actions/workflows/build.yaml

[ci-18]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-18]: https://github.com/jimboid/biosim-python-workshop/actions/workflows/build.yaml

[ci-19]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-19]: https://github.com/jimboid/biosim-qmmm-workshop/actions/workflows/build.yaml

[ci-20]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-20]: https://github.com/jimboid/biosim-structure-validation-workshop/actions/workflows/build.yaml

[ci-21]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-21]: https://github.com/jimboid/biosim-ubiquitin-analysis-workshop/actions/workflows/build.yaml

[ci-22]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml/badge.svg?branch=main
[ci-link-22]: https://github.com/jimboid/biosim-uglymol/actions/workflows/build.yaml
