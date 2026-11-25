Nava OS is a linux operating system that can be built from the ground up using a basic toolchain/filesystem. Nava OS currently uses the basic toolchain/filesystem from the Multilib Linux
From Scratch (MLFS) (SysV Edition) and there after helps to build the individual packages so the OS gets very clean build packages.

- uses the basic shell script packaging system from Slackware's pkgtools and CRUX's pkgutils's pkgmk.
- supports both 64-bit and 32-bit libraries in each package as much as possible.

Note: The above approach of using MLFS may change in future because there is issue with the files that get generated at the end that form the footprint as the current system is not able to
create different footprints based on the path chosen.

Last but not the least, I would like to dedicate Nava OS to my parents - Ramesh GK
