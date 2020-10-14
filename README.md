# apps-tools
Tools for apps stack

An apps stack is defined as a directory of the form
```
/sfs/applications/YYYYMM[_build]
```

This repository contains the following Bash scripts:

## EasyBuild
- `apprm` - Remove an app from an (or a list of) apps stack(s)
- `appsync` - Sync an app between two apps stacks
- `container2module` - Pull container and install as module
- `easyblocksync` - Sync easyblocks
- `goolfc` - Automatic installation of entire goolfc toolchain

## Vendor
- `vendorchown` - Change group ownership for vendor software

## Apps stack management
- `find_default` - Find default version of compilers and toolchains
- `find_incomplete_install` - Find potentially incomplete EasyBuild installations
- `set_default` - Set default version of compilers and toolchains
- `stackdiff` - Compare two apps stacks via `tree`

## Others
- `getlib` - Find library dependencies of binaries
- `getpylib` - Find library dependencies of Python packages
- `jkrollout` - Install custom Jupyter kernel for a container
- `pypkgver` - Find latest version of Python packages via conda or pip
