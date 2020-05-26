About test_package
==================

Home: https://github.com/hadim/read-roi

Package license: 

Feedstock license: BSD 3-Clause

Summary: Read ROI files .zip or .roi generated with ImageJ.



Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
            <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=linux&configuration=linux_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=linux&configuration=linux_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=osx&configuration=osx_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=osx&configuration=osx_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=win&configuration=win_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>win_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/invivoai-forge/feedstock-builds/_build/latest?definitionId=&branchName=master">
                  <img src="https://dev.azure.com/invivoai-forge/feedstock-builds/_apis/build/status/test_package-feedstock?branchName=master&jobName=win&configuration=win_python3.7.____cpython" alt="variant">
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
| [![Conda Recipe](https://img.shields.io/badge/recipe-test_package-green.svg)](https://anaconda.org/invivoai/test_package) | [![Conda Downloads](https://img.shields.io/conda/dn/invivoai/test_package.svg)](https://anaconda.org/invivoai/test_package) | [![Conda Version](https://img.shields.io/conda/vn/invivoai/test_package.svg)](https://anaconda.org/invivoai/test_package) | [![Conda Platforms](https://img.shields.io/conda/pn/invivoai/test_package.svg)](https://anaconda.org/invivoai/test_package) |

Installing test_package
=======================

Installing `test_package` from the `invivoai` channel can be achieved by adding `invivoai` to your channels with:

```
conda config --add channels invivoai
```

Once the `invivoai` channel has been enabled, `test_package` can be installed with:

```
conda install test_package
```

It is possible to list all of the versions of `test_package` available on your platform with:

```
conda search test_package --channel invivoai
```




Updating test_package-feedstock
===============================

If you would like to improve the test_package recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`invivoai` channel, whereupon the built conda packages will be available for
everybody to install and use from the `invivoai` channel.
Note that all branches in the invivoai-forge/test_package-feedstock are
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

* [@hadim](https://github.com/hadim/)

