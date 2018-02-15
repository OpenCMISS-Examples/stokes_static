=============
Stokes Static
=============

Stokes equation is a linearised form of the Navier-Stokes equations in the limit of small Reynolds number.
This equation, also named creeping flow, is a type of fluid flow where advective inertial forces are small compared with viscous forces.
The static form of the Stokes equation is implemented in this example.


Building the example
====================

The fortran version of the example can be configured and built with CMake::

  git clone https://github.com/OpenCMISS-Examples/stokes_static.git
  mkdir stokes_static-build
  cd stokes_static-build
  cmake -DOpenCMISSLibs_DIR=~/opencmiss/install/  ../stokes_static/
  make


Running the example
===================

Fortran version::

  cd ./src/fortran/
  ./stokes_static_fortran

The results can be visualised by running `visualise.com <./src/fortran/visualise.com>`_ with the `Cmgui visualiser <http://physiomeproject.org/software/opencmiss/cmgui/download>`_.


Prerequisites
=============

There are no additional input files required for this example as it is self-contained.


License
=======

License applicable to this example is described in `LICENSE <./LICENSE>`_.
