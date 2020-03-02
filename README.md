# apps-tools
Tools for apps stack

An apps stack is defined as a directory of the form
```
/sfs/applications/YYYYMM[_build]
```

This repository contains the following Bash scripts:

## EasyBuild
- `appsync` - Sync an app between two apps stacks
- `apprm` - Remove an app from an (or a list of) apps stack(s)
- `easyblocksync` - Sync easyblocks

## Vendor
- `vendorchown` - Change group ownership for vendor software

## Apps stack management
- `stackdiff` - Compare two apps stacks via `tree`
- `find_incomplete_install` - Find potentially incomplete EasyBuild installations
