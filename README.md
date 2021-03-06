# Code-D

Adds D language support for visual studio code.

Also [available for Atom](https://github.com/Pure-D/atomize-d)!

## Features

* Autocompletion
* Code formatting
* Static linting
* Outlining and searching for symbols
* and [much more](https://github.com/Pure-D/code-d/wiki)

## Installation

### Prerequirements:
D compiler with environment variables set. Downloads [here](https://dlang.org/download.html), details [here](https://wiki.dlang.org/Compilers)

### Dependencies:

code-d will install [serve-d](https://github.com/Pure-D/serve-d),
[dcd](https://github.com/dlang-community/DCD) and [dub](https://code.dlang.org/download)
if they are not already installed.

### code-d installation

This assumes [serve-d](https://github.com/Pure-D/serve-d) is already installed.

* Automatic:
  Open Visual Studio Code and install the _code-d_ extension the normal way:

  ```
  ext install webfreak.code-d
  ```

* Manual (if the automatic way doesn't work)

    ```
    cd ~/.vscode/extensions/
    git clone https://github.com/Pure-D/code-d.git
    cd code-d
    npm install
    tsc -p .
    ```

## License

MIT - Look in [LICENSE.md](LICENSE.md) for more information

## Special Thanks

Thanks to @Hackerpilot for his great software used here and the D package registry
for their great package manager and library "dub"

## Authors

* Dan "Wild" Printzell
* Jan "WebFreak" Jurzitza

## Issues

Please submit issues to [github](https://github.com/Pure-D/code-d)
