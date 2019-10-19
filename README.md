About eman-packaging-feedstock
==============================

Home: 

Package license: 

Feedstock license: BSD 3-Clause

Summary: Meta-package for eman packaging



Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/cryoem/eman-packaging-feedstock">
        <img alt="Linux" src="https://img.shields.io/circleci/project/github/cryoem/eman-packaging-feedstock/master.svg?label=Linux">
      </a>
    </td>
  </tr><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.org/cryoem/eman-packaging-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/cryoem/eman-packaging-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/cryoem/eman-packaging-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/cryoem/eman-packaging-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
            <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/eman-packaging-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux</td>
              <td>
                <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
                  <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/eman-packaging-feedstock?branchName=master&jobName=linux&configuration=linux_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx</td>
              <td>
                <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
                  <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/eman-packaging-feedstock?branchName=master&jobName=osx&configuration=osx_" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win</td>
              <td>
                <a href="https://dev.azure.com/cryoem/feedstock-builds/_build/latest?definitionId=blank&branchName=master">
                  <img src="https://dev.azure.com/cryoem/feedstock-builds/_apis/build/status/eman-packaging-feedstock?branchName=master&jobName=win&configuration=win_" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-eman--packaging--feedstock-green.svg)](https://anaconda.org/cryoem/eman-packaging-feedstock) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/eman-packaging-feedstock.svg)](https://anaconda.org/cryoem/eman-packaging-feedstock) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/eman-packaging-feedstock.svg)](https://anaconda.org/cryoem/eman-packaging-feedstock) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/eman-packaging-feedstock.svg)](https://anaconda.org/cryoem/eman-packaging-feedstock) |

Installing eman-packaging-feedstock
===================================

Installing `eman-packaging-feedstock` from the `cryoem` channel can be achieved by adding `cryoem` to your channels with:

```
conda config --add channels cryoem
```

Once the `cryoem` channel has been enabled, `eman-packaging-feedstock` can be installed with:

```
conda install eman-packaging-feedstock
```

It is possible to list all of the versions of `eman-packaging-feedstock` available on your platform with:

```
conda search eman-packaging-feedstock --channel cryoem
```




Updating eman-packaging-feedstock-feedstock
===========================================

If you would like to improve the eman-packaging-feedstock recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cryoem` channel.
Note that all branches in the cryoem/eman-packaging-feedstock-feedstock are
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


