# pyicu-build
Build [PyICU](https://gitlab.pyicu.org/main/pyicu) wheels for Windows using [GitHub Actions](https://github.com/cgohlke/pyicu-build/actions/workflows/wheel.yml) and [ICU binaries](https://github.com/unicode-org/icu/releases).

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/pyicu-build/releases) page.

Install a wheel on the command line, for example for Python 3.12 64-bit:

    $ py.exe -3.12 -m pip install PyICU-2.13-cp312-cp312-win_amd64.whl
