# PyOOMUSH

> An object-oriented dynamic text-based interactive MUSH, or multi-user shared environment.

> © 2006-2022 Alice Bevan-McGregor and contributors.

> https://github.com/amcgregor/pyoomush


## Contents

1. [Overview](#overview)

2. [Installation](#installation)

	1. [Development Version](#development-version)

3. [Getting Started](#getting-started)

4. [Version History](#version-history)

5. [License](#license)


## Overview

<!-- TBD -->


## Installation

Installing `pyoomush` is easy, just execute the following in a terminal:

	pip install pyoomush

**Note:** We *strongly* recommend always using a container, virtualization, or sandboxing environment of some kind when developing using Python. We highly recommend use of the Python standard [`venv` (_"virtual environment"_) mechanism][venv].

If you add `pyoomush` to the `install_requires` argument of the call to `setup()` in your application's `setup.py` or `setup.cfg` files, PyOOMUSH will be automatically installed and made available when your own application or library is installed. Use `pyoomush ~= 1.0.0` to get all bug fixes for the 1.0.0 release while ensuring that large breaking changes are not installed by limiting to the same major/minor, >= the given patch level.

This package has the following dependencies:

* A Python interpreter compatible with CPython 3.8 and or newer, i.e. official CPython or Pypy.


### Development Version

Development takes place on [GitHub][github] in the [pyoomush][repo] project. Issue tracking, documentation, and downloads are provided there.

Installing the current development version requires [Git][git]), a distributed source code management system. If you have Git you can run the following to download and *link* the development version into your Python runtime:

	git clone https://github.com/amcgregor/pyoomush.git
	pip install -e 'pyoomush[development]'

You can then upgrade to the latest version at any time, from within that source folder:

	git pull
	pip install -e '.[development]'

If you would like to make changes and contribute them back to the project, fork the GitHub project, make your changes, and submit a pull request. This process is beyond the scope of this documentation; for more information see [GitHub's documentation][ghhelp].


## Getting Started

Describe the basic steps required to utilize this package. Provide additional sections or subsections as needed. If this documentation exceeds an additional section or two, consider writing a GitBook instead.


## Version History

This project has yet to make any releases. When it does, each release should be documented here with a sub-section for the version, and a bulleted list of itemized changes tagged with the kind of change, e.g. *fixed*, *added*, *removed*, or *deprecated*.


## License

PyOOMUSH has been released under the MIT Open Source license.

### The MIT License

Copyright © 2006–2022 Alice Bevan-McGregor and contributors.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


[venv]: https://docs.python.org/3/tutorial/venv.html

[git]: http://git-scm.com/
[repo]: https://github.com/amcgregor/pyoomush/
[github]: https://github.com/
[ghhelp]: https://help.github.com/


[ghwatch]: https://img.shields.io/github/watchers/amcgregor/pyoomush.svg?style=social&label=Watch "Subscribe to project activity on GitHub."
[ghstar]: https://img.shields.io/github/stars/amcgregor/pyoomush.svg?style=social&label=Star "Star this project on GitHub."
[ghsubscription]: https://github.com/amcgregor/pyoomush/subscription
[ghfork]: https://img.shields.io/github/forks/amcgregor/pyoomush.svg?style=social&label=Fork "Fork this project on Github."
[ghfork_]: https://github.com/marrow/cinje/fork

[ghissues]: http://img.shields.io/github/issues-raw/amcgregor/pyoomush.svg?style=flat "Github Issues"
[ghissues_]: https://github.com/amcgregor/pyoomush/issues
[ghsince]: https://img.shields.io/github/commits-since/amcgregor/pyoomush/$version.svg "Changes since last release."
[ghsince_]: https://github.com/amcgregor/pyoomush/commits/develop
[ghtag]: https://img.shields.io/github/tag/amcgregor/pyoomush.svg "Latest Github tagged release."
[ghtag_]: https://github.com/amcgregor/pyoomush/tree/$version
[latestversion]: http://img.shields.io/pypi/v/pyoomush.svg?style=flat "Latest released version on Pypi."
[latestversion_]: https://pypi.python.org/pypi/pyoomush

[cake]: http://img.shields.io/badge/cake-lie-1b87fb.svg?style=flat

