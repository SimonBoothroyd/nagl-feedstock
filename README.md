About nagl
==========

Home: https://github.com/simonboothroyd/nagl

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/simonboothroyd/nagl-feedstock/blob/master/LICENSE.txt)

Summary: Graph convolutional networks learning molecular force fields.

Development: https://github.com/simonboothroyd/nagl

A framework for applying graph convolutional networks to molecules,
with a focus on learning continuous "atom-type" embeddings and from
these classical molecule force field parameters.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/simonboothroyd/feedstock-builds/_build/latest?definitionId=6&branchName=master">
        <img src="https://dev.azure.com/simonboothroyd/feedstock-builds/_apis/build/status/nagl-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-nagl-green.svg)](https://anaconda.org/simonboothroyd/nagl) | [![Conda Downloads](https://img.shields.io/conda/dn/simonboothroyd/nagl.svg)](https://anaconda.org/simonboothroyd/nagl) | [![Conda Version](https://img.shields.io/conda/vn/simonboothroyd/nagl.svg)](https://anaconda.org/simonboothroyd/nagl) | [![Conda Platforms](https://img.shields.io/conda/pn/simonboothroyd/nagl.svg)](https://anaconda.org/simonboothroyd/nagl) |

Installing nagl
===============

Installing `nagl` from the `simonboothroyd` channel can be achieved by adding `simonboothroyd` to your channels with:

```
conda config --add channels simonboothroyd
```

Once the `simonboothroyd` channel has been enabled, `nagl` can be installed with:

```
conda install nagl
```

It is possible to list all of the versions of `nagl` available on your platform with:

```
conda search nagl --channel simonboothroyd
```




Updating nagl-feedstock
=======================

If you would like to improve the nagl recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`simonboothroyd` channel, whereupon the built conda packages will be available for
everybody to install and use from the `simonboothroyd` channel.
Note that all branches in the simonboothroyd/nagl-feedstock are
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

* [@SimonBoothroyd](https://github.com/SimonBoothroyd/)

