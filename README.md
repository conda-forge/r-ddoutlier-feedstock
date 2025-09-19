About r-ddoutlier-feedstock
===========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-ddoutlier-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/jhmadsen/DDoutlier

Package license: MIT

Summary: Outlier detection in multidimensional domains. Implementation of notable distance and density-based outlier algorithms. Allows users to identify local outliers by comparing observations to their nearest neighbors, reverse nearest neighbors, shared neighbors or natural neighbors. For distance-based approaches, see Knorr, M., & Ng, R. T. (1997) <doi:10.1145/782010.782021>, Angiulli, F., & Pizzuti, C. (2002) <doi:10.1007/3-540-45681-3_2>, Hautamaki, V., & Ismo, K. (2004) <doi:10.1109/ICPR.2004.1334558> and Zhang, K., Hutter, M. & Jin, H. (2009) <doi:10.1007/978-3-642-01307-2_84>. For density-based approaches, see Tang, J., Chen, Z., Fu, A. W. C., & Cheung, D. W. (2002) <doi:10.1007/3-540-47887-6_53>, Jin, W., Tung, A. K. H., Han, J., & Wang, W. (2006) <doi:10.1007/11731139_68>, Schubert, E., Zimek, A. & Kriegel, H-P. (2014) <doi:10.1137/1.9781611973440.63>, Latecki, L., Lazarevic, A. & Prokrajac, D. (2007) <doi:10.1007/978-3-540-73499-4_6>, Papadimitriou, S., Gibbons, P. B., & Faloutsos, C. (2003) <doi:10.1109/ICDE.2003.1260802>, Breunig, M. M., Kriegel, H.-P., Ng, R. T., & Sander, J. (2000) <doi:10.1145/342009.335388>, Kriegel, H.-P., Kröger, P., Schubert, E., & Zimek, A. (2009) <doi:10.1145/1645953.1646195>, Zhu, Q., Feng, Ji. & Huang, J. (2016) <doi:10.1016/j.patrec.2016.05.007>, Huang, J., Zhu, Q., Yang, L. & Feng, J. (2015) <doi:10.1016/j.knosys.2015.10.014>, Tang, B. & Haibo, He. (2017) <doi:10.1016/j.neucom.2017.02.039> and Gao, J., Hu, W., Zhang, X. & Wu, Ou. (2011) <doi:10.1007/978-3-642-20847-8_23>.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=22043&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-ddoutlier-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--ddoutlier-green.svg)](https://anaconda.org/conda-forge/r-ddoutlier) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-ddoutlier.svg)](https://anaconda.org/conda-forge/r-ddoutlier) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-ddoutlier.svg)](https://anaconda.org/conda-forge/r-ddoutlier) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-ddoutlier.svg)](https://anaconda.org/conda-forge/r-ddoutlier) |

Installing r-ddoutlier
======================

Installing `r-ddoutlier` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-ddoutlier` can be installed with `conda`:

```
conda install r-ddoutlier
```

or with `mamba`:

```
mamba install r-ddoutlier
```

It is possible to list all of the versions of `r-ddoutlier` available on your platform with `conda`:

```
conda search r-ddoutlier --channel conda-forge
```

or with `mamba`:

```
mamba search r-ddoutlier --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-ddoutlier --channel conda-forge

# List packages depending on `r-ddoutlier`:
mamba repoquery whoneeds r-ddoutlier --channel conda-forge

# List dependencies of `r-ddoutlier`:
mamba repoquery depends r-ddoutlier --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

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


Updating r-ddoutlier-feedstock
==============================

If you would like to improve the r-ddoutlier recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-ddoutlier-feedstock are
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

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)
* [@jackfeltham](https://github.com/jackfeltham/)

