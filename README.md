About libmetatomic-torch-feedstock
==================================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/libmetatomic-torch-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/metatensor/metatomic

Package license: BSD-3-Clause

Summary: Atomistic machine learning models you can use everywhere for everything

Documentation: https://docs.metatensor.org/metatomic/

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-libmetatomic--torch-green.svg)](https://anaconda.org/metatensor/libmetatomic-torch) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/libmetatomic-torch.svg)](https://anaconda.org/metatensor/libmetatomic-torch) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/libmetatomic-torch.svg)](https://anaconda.org/metatensor/libmetatomic-torch) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/libmetatomic-torch.svg)](https://anaconda.org/metatensor/libmetatomic-torch) |

Installing libmetatomic-torch
=============================

Installing `libmetatomic-torch` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `libmetatomic-torch` can be installed with `conda`:

```
conda install libmetatomic-torch
```

or with `mamba`:

```
mamba install libmetatomic-torch
```

It is possible to list all of the versions of `libmetatomic-torch` available on your platform with `conda`:

```
conda search libmetatomic-torch --channel metatensor
```

or with `mamba`:

```
mamba search libmetatomic-torch --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search libmetatomic-torch --channel metatensor

# List packages depending on `libmetatomic-torch`:
mamba repoquery whoneeds libmetatomic-torch --channel metatensor

# List dependencies of `libmetatomic-torch`:
mamba repoquery depends libmetatomic-torch --channel metatensor
```




Updating libmetatomic-torch-feedstock
=====================================

If you would like to improve the libmetatomic-torch recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/libmetatomic-torch-feedstock are
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

* [@Haozeke](https://github.com/Haozeke/)
* [@Luthaf](https://github.com/Luthaf/)
* [@PicoCentauri](https://github.com/PicoCentauri/)

