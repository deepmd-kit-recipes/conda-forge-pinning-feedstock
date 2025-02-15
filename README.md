About conda-forge-pinning
=========================

Home: https://conda-forge.org/docs/maintainer/infrastructure.html#conda-forge-pinning

Package license: BSD-3-Clause

Feedstock license: [BSD-3-Clause](https://github.com/deepmd-kit-recipes/conda-forge-pinning-feedstock/blob/master/LICENSE.txt)

Summary: The baseline versions of software for the conda-forge ecosystem

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/conda-forge-pinning-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-conda--forge--pinning-green.svg)](https://anaconda.org/deepmodeling/conda-forge-pinning) | [![Conda Downloads](https://img.shields.io/conda/dn/deepmodeling/conda-forge-pinning.svg)](https://anaconda.org/deepmodeling/conda-forge-pinning) | [![Conda Version](https://img.shields.io/conda/vn/deepmodeling/conda-forge-pinning.svg)](https://anaconda.org/deepmodeling/conda-forge-pinning) | [![Conda Platforms](https://img.shields.io/conda/pn/deepmodeling/conda-forge-pinning.svg)](https://anaconda.org/deepmodeling/conda-forge-pinning) |

Installing conda-forge-pinning
==============================

Installing `conda-forge-pinning` from the `deepmodeling` channel can be achieved by adding `deepmodeling` to your channels with:

```
conda config --add channels deepmodeling
conda config --set channel_priority strict
```

Once the `deepmodeling` channel has been enabled, `conda-forge-pinning` can be installed with:

```
conda install conda-forge-pinning
```

It is possible to list all of the versions of `conda-forge-pinning` available on your platform with:

```
conda search conda-forge-pinning --channel deepmodeling
```




Updating conda-forge-pinning-feedstock
======================================

If you would like to improve the conda-forge-pinning recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`deepmodeling` channel, whereupon the built conda packages will be available for
everybody to install and use from the `deepmodeling` channel.
Note that all branches in the deepmd-kit-recipes/conda-forge-pinning-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@njzjz](https://github.com/njzjz/)

