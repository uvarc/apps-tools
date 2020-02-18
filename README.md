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
- `find_incomplete_install` - Find potentially incomplete EasyBuild installations

## Vendor
- `vendorchown` - Change group ownership for vendor software

## Apps stack comparison
- `compare_stack` - Compare two apps stacks via `tree`
- `tree2list` - Tidy up into a list
- `list2md` - Combine 5 lists (core, compiler, mpi, toolchains, container) and convert into markdown
