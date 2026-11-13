> [!NOTE]
> **This is the edulution fork of [linuxmuster-common](https://github.com/linuxmuster/linuxmuster-common).**
> We build on the great work of the linuxmuster.net community. Maintaining our own
> fork gives us the flexibility to ship security fixes and new features to edulution
> installations quickly, and we actively contribute our changes back to the community
> project. The packages are published at [package.edulution.io](https://package.edulution.io).

# linuxmuster-common
Common files for linuxmuster.net (since v7.3)

See issue [#156](https://github.com/linuxmuster/linuxmuster-base7/issues/156).

Compared to version 7.2, the following files have been renamed and moved to the package linuxmuster-common:

* from linuxmuster-base7
  * `/usr/lib/linuxmuster/constants.py` -> `/usr/lib/linuxmuster/environment.py`
  * `/usr/share/linuxmuster/defaults.sh` -> `/usr/share/linuxmuster/environment.sh`
* from linuxmuster-linbo7
  * `/usr/share/linuxmuster/linbo/helperfunctions.sh` -> `/usr/share/linuxmuster/helperfunctions.sh`
