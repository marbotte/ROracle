# ROracle

This repo is merely a way to test some options for installing ROracle in some Windows machines through the package remote.

**I AM NOT THE AUTHOR OF THE PACKAGE**, Denis Mukhin, David A. James and Jake Luciani are, please refer to <https://cran.r-project.org/web/packages/ROracle/index.html> for any information about the package.


I just wanted to test the method described in <https://stackoverflow.com/questions/52215350/roracle-package-installation-failure>, basically adding the line:

> cp ${ROCI_INC}/ociver.h ./src/oci

in the file configure.win.

Does not seem much, but after 3 hours of desperate search for a solution in a windows machine that I do not use much, making that and installing the package through:

> devtools::install.packages("marbotte/ROracle")

simply worked!
