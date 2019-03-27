About sixs
==========

Home: https://bitbucket.org/petebunting/6s

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: A basic RT code used for atmospheric correction & atmospheric simulations

The 6S code is a basic RT code used for calculation of lookup
tables in the MODIS atmospheric correction algorithm.
It enables accurate simulations of satellite and plane observation,
accounting for elevated targets, use of anisotropic and lambertian surfaces
and calculation of gaseous absorption. 6S website is http://6s.ltdri.org.


Current build status
====================


<table><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/conda-forge/sixs-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/conda-forge/sixs-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
<<<<<<< HEAD
              <td>osx_fortran_compiler_version4</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master&jobName=osx&configuration=osx_fortran_compiler_version4" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_fortran_compiler_version7</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master&jobName=osx&configuration=osx_fortran_compiler_version7" alt="variant">
=======
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
>>>>>>> MNT: Re-rendered with conda-build 3.17.8, conda-smithy 3.3.2, and conda-forge-pinning 2019.03.18
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1922&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/sixs-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
<<<<<<< HEAD
![ppc64le disabled](https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg)
=======
>>>>>>> MNT: Re-rendered with conda-build 3.17.8, conda-smithy 3.3.2, and conda-forge-pinning 2019.03.18
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-sixs-green.svg)](https://anaconda.org/conda-forge/sixs) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/sixs.svg)](https://anaconda.org/conda-forge/sixs) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/sixs.svg)](https://anaconda.org/conda-forge/sixs) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/sixs.svg)](https://anaconda.org/conda-forge/sixs) |

Installing sixs
===============

Installing `sixs` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `sixs` can be installed with:

```
conda install sixs
```

It is possible to list all of the versions of `sixs` available on your platform with:

```
conda search sixs --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating sixs-feedstock
=======================

If you would like to improve the sixs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/sixs-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@danclewley](https://github.com/danclewley/)
* [@robintw](https://github.com/robintw/)

