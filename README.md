# PIM-DM (Dense Multicast) aka pimdd

## Build & install

Building process requires directories from `include/netinet` and `linux/netinet` of [pimd](https://github.com/troglobit/pimd/tree/master/include) project installed to your include path(i.e. /usr/include). Otherwise, pimdd usually will not build.

To build and install:
* Execute `make`;
* Execute `make install` as root. Optional `PREFIX` variable used to specify root of installation;

## TBD

* Service file(sysV and systemd ones);
* Refactoring of system detection(Linux or other system) in Makefile, check portablity of flags;

## More info

Read old README file in the source files.
