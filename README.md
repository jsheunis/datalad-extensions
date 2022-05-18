# DataLad healthchecks

This is a "dashboard" of various CIs of DataLad, its extensions, and underlying
3-rd party projects like git-annex.

**This README.md is autogenerated - do not edit.
  See [CONTRIBUTING.md](CONTRIBUTING.md) for more information.**

## Git-annex Status

 - Conda: ![Conda?](https://anaconda.org/conda-forge/git-annex/badges/version.svg)
    ![Updated](https://anaconda.org/conda-forge/git-annex/badges/latest_release_relative_date.svg)
    ![Platforms?](https://anaconda.org/conda-forge/git-annex/badges/platforms.svg)
 - Current snapshot build/tests + DataLad tests:
    [![Build git-annex snapshot](https://github.com/datalad/datalad-extensions/workflows/Build%20git-annex%20snapshot/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3A%22Build+git-annex+snapshot%22)

## DataLad Status

 [![DataLad GitHub release](https://img.shields.io/github/release/datalad/datalad.svg)](https://GitHub.com/datalad/datalad/releases/)
 [![DataLad PyPI version fury.io](https://badge.fury.io/py/datalad.svg)](https://pypi.python.org/pypi/datalad/)
 ![Conda?](https://anaconda.org/conda-forge/datalad/badges/version.svg)
 - **CIs**:
   Travis: 
   `master`[![Travis tests status: master](https://app.travis-ci.com/datalad/datalad.svg?branch=master)](https://app.travis-ci.com/github/datalad/datalad/branches), 
   `maint` [![Travis tests status: master](https://app.travis-ci.com/datalad/datalad.svg?branch=maint)](https://app.travis-ci.com/github/datalad/datalad/branches);
   Appveyor:
   `master` [![Build status](https://ci.appveyor.com/api/projects/status/github/datalad/datalad?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad/branch/master)
   `maint` [![Build status](https://ci.appveyor.com/api/projects/status/github/datalad/datalad?branch=maint&svg=true)](https://ci.appveyor.com/project/mih/datalad/branch/maint)
 - Misc:
   [![codecov.io](https://codecov.io/github/datalad/datalad/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad?branch=master)
   [![Documentation](https://readthedocs.org/projects/datalad/badge/?version=latest)](http://datalad.rtfd.org)

## DataLad Extensions Status

 | Name | Release | PyPI Release | Conda Release | CI: Released + DL master | CI: Released + DL maint | CI: master + DL Release | Codecov | Issue Resolution | Open Issues | 
 | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | 
 | [datalad_neuroimaging](https://github.com/datalad/datalad-neuroimaging) | [![?](https://img.shields.io/github/release/datalad/datalad-neuroimaging.svg)](https://GitHub.com/datalad/datalad-neuroimaging/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-neuroimaging.svg)](https://pypi.python.org/pypi/datalad-neuroimaging/) | ![-](https://anaconda.org/conda-forge/datalad-neuroimaging/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_neuroimaging-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_neuroimaging-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_neuroimaging-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_neuroimaging-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-neuroimaging?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-neuroimaging/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-neuroimaging/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-neuroimaging?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-neuroimaging.svg)](http://isitmaintained.com/project/datalad/datalad-neuroimaging "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-neuroimaging.svg)](http://isitmaintained.com/project/datalad/datalad-neuroimaging "Percentage of issues still open") | 
 | [datalad_container](https://github.com/datalad/datalad-container) | [![?](https://img.shields.io/github/release/datalad/datalad-container.svg)](https://GitHub.com/datalad/datalad-container/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-container.svg)](https://pypi.python.org/pypi/datalad-container/) | ![-](https://anaconda.org/conda-forge/datalad-container/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_container-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_container-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_container-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_container-maint) | [![master+Released Datalad](https://travis-ci.com/datalad/datalad-container.svg?branch=master)](https://travis-ci.com/github/datalad/datalad-container) | [![codecov.io](https://codecov.io/github/datalad/datalad-container/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-container?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-container.svg)](http://isitmaintained.com/project/datalad/datalad-container "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-container.svg)](http://isitmaintained.com/project/datalad/datalad-container "Percentage of issues still open") | 
 | [datalad_metalad](https://github.com/datalad/datalad-metalad) | [![?](https://img.shields.io/github/release/datalad/datalad-metalad.svg)](https://GitHub.com/datalad/datalad-metalad/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-metalad.svg)](https://pypi.python.org/pypi/datalad-metalad/) | ![-](https://anaconda.org/conda-forge/datalad-metalad/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_metalad-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_metalad-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_metalad-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_metalad-maint) | [![master+Released Datalad](https://travis-ci.com/datalad/datalad-metalad.svg?branch=master)](https://travis-ci.com/github/datalad/datalad-metalad) | [![codecov.io](https://codecov.io/github/datalad/datalad-metalad/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-metalad?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-metalad.svg)](http://isitmaintained.com/project/datalad/datalad-metalad "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-metalad.svg)](http://isitmaintained.com/project/datalad/datalad-metalad "Percentage of issues still open") | 
 | [datalad_crawler](https://github.com/datalad/datalad-crawler) | [![?](https://img.shields.io/github/release/datalad/datalad-crawler.svg)](https://GitHub.com/datalad/datalad-crawler/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-crawler.svg)](https://pypi.python.org/pypi/datalad-crawler/) | ![-](https://anaconda.org/conda-forge/datalad-crawler/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_crawler-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_crawler-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_crawler-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_crawler-maint) | [![master+Released Datalad](https://travis-ci.com/datalad/datalad-crawler.svg?branch=master)](https://travis-ci.com/github/datalad/datalad-crawler) | [![codecov.io](https://codecov.io/github/datalad/datalad-crawler/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-crawler?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-crawler.svg)](http://isitmaintained.com/project/datalad/datalad-crawler "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-crawler.svg)](http://isitmaintained.com/project/datalad/datalad-crawler "Percentage of issues still open") | 
 | [datalad_osf](https://github.com/datalad/datalad-osf) | [![?](https://img.shields.io/github/release/datalad/datalad-osf.svg)](https://GitHub.com/datalad/datalad-osf/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-osf.svg)](https://pypi.python.org/pypi/datalad-osf/) | ![-](https://anaconda.org/conda-forge/datalad-osf/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_osf-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_osf-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_osf-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_osf-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-osf?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-osf/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-osf/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-osf?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-osf.svg)](http://isitmaintained.com/project/datalad/datalad-osf "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-osf.svg)](http://isitmaintained.com/project/datalad/datalad-osf "Percentage of issues still open") | 
 | [datalad_ukbiobank](https://github.com/datalad/datalad-ukbiobank) | [![?](https://img.shields.io/github/release/datalad/datalad-ukbiobank.svg)](https://GitHub.com/datalad/datalad-ukbiobank/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-ukbiobank.svg)](https://pypi.python.org/pypi/datalad-ukbiobank/) | ![-](https://anaconda.org/conda-forge/datalad-ukbiobank/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_ukbiobank-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_ukbiobank-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_ukbiobank-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_ukbiobank-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-ukbiobank?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-ukbiobank/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-ukbiobank/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-ukbiobank?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-ukbiobank.svg)](http://isitmaintained.com/project/datalad/datalad-ukbiobank "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-ukbiobank.svg)](http://isitmaintained.com/project/datalad/datalad-ukbiobank "Percentage of issues still open") | 
 | [datalad_mihextras](https://github.com/mih/datalad-mihextras) | [![?](https://img.shields.io/github/release/mih/datalad-mihextras.svg)](https://GitHub.com/mih/datalad-mihextras/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-mihextras.svg)](https://pypi.python.org/pypi/datalad-mihextras/) | ![-](https://anaconda.org/conda-forge/datalad-mihextras/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_mihextras-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_mihextras-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_mihextras-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_mihextras-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/mih/datalad-mihextras?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-mihextras/branch/master) | [![codecov.io](https://codecov.io/github/mih/datalad-mihextras/coverage.svg?branch=master)](https://codecov.io/github/mih/datalad-mihextras?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/mih/datalad-mihextras.svg)](http://isitmaintained.com/project/mih/datalad-mihextras "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/mih/datalad-mihextras.svg)](http://isitmaintained.com/project/mih/datalad-mihextras "Percentage of issues still open") | 
 | [datalad_next](https://github.com/datalad/datalad-next) | [![?](https://img.shields.io/github/release/datalad/datalad-next.svg)](https://GitHub.com/datalad/datalad-next/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-next.svg)](https://pypi.python.org/pypi/datalad-next/) | ![-](https://anaconda.org/conda-forge/datalad-next/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_next-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_next-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_next-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_next-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-next?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-next/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-next/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-next?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-next.svg)](http://isitmaintained.com/project/datalad/datalad-next "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-next.svg)](http://isitmaintained.com/project/datalad/datalad-next "Percentage of issues still open") | 
 | [datalad_deprecated](https://github.com/datalad/datalad-deprecated) | [![?](https://img.shields.io/github/release/datalad/datalad-deprecated.svg)](https://GitHub.com/datalad/datalad-deprecated/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-deprecated.svg)](https://pypi.python.org/pypi/datalad-deprecated/) | ![-](https://anaconda.org/conda-forge/datalad-deprecated/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_deprecated-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_deprecated-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_deprecated-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_deprecated-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-deprecated?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-deprecated/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-deprecated/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-deprecated?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-deprecated.svg)](http://isitmaintained.com/project/datalad/datalad-deprecated "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-deprecated.svg)](http://isitmaintained.com/project/datalad/datalad-deprecated "Percentage of issues still open") | 
 | [datalad_xnat](https://github.com/datalad/datalad-xnat) | [![?](https://img.shields.io/github/release/datalad/datalad-xnat.svg)](https://GitHub.com/datalad/datalad-xnat/releases/) | [![PyPI version fury.io](https://badge.fury.io/py/datalad-xnat.svg)](https://pypi.python.org/pypi/datalad-xnat/) | ![-](https://anaconda.org/conda-forge/datalad-xnat/badges/version.svg) | [![Released+DataLad master](https://github.com/datalad/datalad-extensions/workflows/test-datalad_xnat-master/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_xnat-master) | [![Released+DataLad maint](https://github.com/datalad/datalad-extensions/workflows/test-datalad_xnat-maint/badge.svg)](https://github.com/datalad/datalad-extensions/actions?query=workflow%3Atest-datalad_xnat-maint) | [![master+Released Datalad](https://ci.appveyor.com/api/projects/status/github/datalad/datalad-xnat?branch=master&svg=true)](https://ci.appveyor.com/project/mih/datalad-xnat/branch/master) | [![codecov.io](https://codecov.io/github/datalad/datalad-xnat/coverage.svg?branch=master)](https://codecov.io/github/datalad/datalad-xnat?branch=master) | [![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/datalad/datalad-xnat.svg)](http://isitmaintained.com/project/datalad/datalad-xnat "Average time to resolve an issue") | [![Percentage of issues still open](http://isitmaintained.com/badge/open/datalad/datalad-xnat.svg)](http://isitmaintained.com/project/datalad/datalad-xnat "Percentage of issues still open") | 
