# Algorithm for Quadratic Pseudo Boolean Optimization (QPBO)
Implemented by Vladimir Kolmogorov (2006-2008). Original code available at: http://pub.ist.ac.at/~vnk/software.html

## Modified as a library
Modified original meson.build by Stefan Haller (https://github.com/fgrsnau/libqpbo)

This port is intended to be used as a subproject in a meson. Builds as a static library.

Build within parent project by linking the dependency via

    libqpbo_proj  = subproject('libqpbo')
    libqpbo_dep   = libqpbo_proj.get_variable('libqpbo_dep')

See Meson documentation on subprojects for details.
(https://mesonbuild.com/Subprojects.html)