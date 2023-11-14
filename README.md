About opencamlib-feedstock
==========================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/opencamlib-feedstock/blob/main/LICENSE.txt)

Home: http://www.anderswallin.net/CAM/

Package license: LGPL-2.1-or-later

Summary: OpenCAMLib (ocl)

Development: https://github.com/aewallin/opencamlib

Documentation: http://www.anderswallin.net/CAM/

OpenCAMLib (ocl) is a C++ library for creating toolpaths for CNC-machines such as mills and lathes.

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-opencamlib-green.svg)](https://anaconda.org/freecad/opencamlib) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/opencamlib.svg)](https://anaconda.org/freecad/opencamlib) | [![Conda Version](https://img.shields.io/conda/vn/freecad/opencamlib.svg)](https://anaconda.org/freecad/opencamlib) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/opencamlib.svg)](https://anaconda.org/freecad/opencamlib) |

Installing opencamlib
=====================

Installing `opencamlib` from the `freecad` channel can be achieved by adding `freecad` to your channels with:

```
conda config --add channels freecad
conda config --set channel_priority strict
```

Once the `freecad` channel has been enabled, `opencamlib` can be installed with `conda`:

```
conda install opencamlib
```

or with `mamba`:

```
mamba install opencamlib
```

It is possible to list all of the versions of `opencamlib` available on your platform with `conda`:

```
conda search opencamlib --channel freecad
```

or with `mamba`:

```
mamba search opencamlib --channel freecad
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search opencamlib --channel freecad

# List packages depending on `opencamlib`:
mamba repoquery whoneeds opencamlib --channel freecad

# List dependencies of `opencamlib`:
mamba repoquery depends opencamlib --channel freecad
```




Updating opencamlib-feedstock
=============================

If you would like to improve the opencamlib recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/opencamlib-feedstock are
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

* [@looooo](https://github.com/looooo/)
* [@vespakoen](https://github.com/vespakoen/)

