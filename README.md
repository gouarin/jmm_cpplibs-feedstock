About jmm_cpplibs
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

Home: 

Package license: Apache License, Version 2.0

Feedstock license: BSD 3-Clause

Summary: 



Current build status
====================

[![Linux](https://img.shields.io/circleci/project/github/Mirebeau/jmm_cpplibs-feedstock/master.svg?label=Linux)](https://circleci.com/gh/Mirebeau/jmm_cpplibs-feedstock)
[![OSX](https://img.shields.io/travis/Mirebeau/jmm_cpplibs-feedstock/master.svg?label=macOS)](https://travis-ci.org/Mirebeau/jmm_cpplibs-feedstock)
![Windows disabled](https://img.shields.io/badge/Windows-disabled-lightgrey.svg)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-jmm_cpplibs-green.svg)](https://anaconda.org/mirebeau/jmm_cpplibs) | [![Conda Downloads](https://img.shields.io/conda/dn/mirebeau/jmm_cpplibs.svg)](https://anaconda.org/mirebeau/jmm_cpplibs) | [![Conda Version](https://img.shields.io/conda/vn/mirebeau/jmm_cpplibs.svg)](https://anaconda.org/mirebeau/jmm_cpplibs) | [![Conda Platforms](https://img.shields.io/conda/pn/mirebeau/jmm_cpplibs.svg)](https://anaconda.org/mirebeau/jmm_cpplibs) |

Installing jmm_cpplibs
======================

Installing `jmm_cpplibs` from the `mirebeau` channel can be achieved by adding `mirebeau` to your channels with:

```
conda config --add channels mirebeau
```

Once the `mirebeau` channel has been enabled, `jmm_cpplibs` can be installed with:

```
conda install jmm_cpplibs
```

It is possible to list all of the versions of `jmm_cpplibs` available on your platform with:

```
conda search jmm_cpplibs --channel mirebeau
```




Updating jmm_cpplibs-feedstock
==============================

If you would like to improve the jmm_cpplibs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`mirebeau` channel, whereupon the built conda packages will be available for
everybody to install and use from the `mirebeau` channel.
Note that all branches in the Mirebeau/jmm_cpplibs-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.
