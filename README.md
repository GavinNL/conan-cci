# Conan Recipe for netcdf

|    | Badge |
|:--------:|:---------:
| Recipe License         | [![License: GPL v3](https://img.shields.io/badge/License-Bincrafters-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
| Source License         | [![License: GPL v3](https://img.shields.io/badge/License-netcdf-blue.svg)](https://www.unidata.ucar.edu/software/netcdf/docs/copyright.html)
| Windows Package Status | [![Build status](https://ci.appveyor.com/api/projects/status/github/GavinNL/conan-netcdf?svg=true)](https://ci.appveyor.com/project/gavinNL/conan-netcdf)|
| Linux Package Status   | [![Build Status](https://travis-ci.org/GavinNL/conan-netcdf.svg?branch=master)](https://travis-ci.org/GavinNL/conan-netcdf)|

## Conan Information

Conan is a C/C++ package manager. For more information see [conan.io](https://conan.io)

This recipe was built using a template provided by [Bincrafters Conan-Templates](https://github.com/bincrafters/conan-templates)

## Conan Package Manager Installation

To install Conan, the best option is to install it from the pip3 repository.

```
pip3 install --user conan
```

## Building the Recipe Locally

This recipe is not hosted on any conan repository such as conan-center or bincrafters and therefore must be built locally. To build the recipe, conan must be installed on your system

```
git clone https://github.com/GavinNL/conan-netcdf.git
cd conan-netcdf
conan create . gavinNL/testing
```

## Issues

This recipe is not actively maintained. Any issues can be posted at https://github.com/GavinNL/conan-netcdf/issues

Pull requests are appreciated.

## General Information

This GIT repository is managed by GavinNL and holds files related to Conan.io.  This recipe only contains information for my needed requirements. It may or may not be useful to you.

## License Information

The base for this Conan Recipe/CI instructions was pulled from the Bincrafter's Repo. Therefore the License for this recipe is the same as the Bincrafters license. This recipie is not maintained by the Bincrafters team.

Bincrafters packages are hosted on [Bintray](https://bintray.com) and contain Open-Source software which is licensed by the software's maintainers and NOT Bincrafters.  For each Open-Source package published by Bincrafters, the packaging process obtains the required license files along with the original source files from the maintainer, and includes these license files in the generated Conan packages.

The contents of this GIT repository are completely separate from the software being packaged and therefore licensed separately.  The license for all files contained in this GIT repository are defined in the [LICENSE.md](LICENSE.md) file in this repository.  The licenses included with all Conan packages published by Bincrafters can be found in the Conan package directories in the following locations, relative to the Conan Cache root (`~/.conan` by default):

### License(s) for packaged software:

    ~/.conan/data/<pkg_name>/<pkg_version>/bincrafters/package/<random_package_id>/license/<LICENSE_FILES_HERE>

*Note :   The most common filenames for OSS licenses are `LICENSE` AND `COPYING` without file extensions.*

### License for Bincrafters recipe:

    ~/.conan/data/<pkg_name>/<pkg_version>/bincrafters/export/LICENSE.md
