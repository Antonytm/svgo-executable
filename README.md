# svgo-executable

`svgo-executable` is standalone binary executable which wraps `svgo` (Scalable Vector Graphics Optimizer) using `pkg` (Node.js binary compiler)

### Why may you need it?

`svgo` requires a Nodejs environment to run. It is not very convenient time to time. Also if you run `svgo` on different machines, there could be installed different versions of `node.exe`, different versions of `npm`. That is why for .NET of Java worlds it could be convenient to have portable `svgo` executable that has no dependencies. You don't need to have `node`, `npm`, bunch of files in `node_modules`. All that you need is just one executable.

## Version Numbering Conventions

As the main goal of repository is just run `svgo` versions in this repository will correspond version of `svgo` that is baked in executables.

## Build Process

In order to make build and release process as transparent as it possible, everything is done using [GitHub actions](https://github.com/Antonytm/svgo-executable/actions). 

## Download

Download the [latest release](https://github.com/Antonytm/svgo-executable/releases/latest):

* svgo-win.exe - Windows
* svgo-macos - MacOS
* svgo-linux - Linux

## Usage

Please refer to [usage of SVGO](https://github.com/svg/svgo).

## Changelog

2022-01-28: Version 2.8.0

Initial version

## Links

- [SVGO](https://github.com/svg/svgo)
- [PKG](https://github.com/vercel/pkg)
