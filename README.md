# pyOccam1DCSEM
1D electromagnetic dipole modelling using Python module distribution of Kerry Key's Occam 1D CSEM code
(forward modelling only)

Installation:
> python3 setup.py configure --prefix=<lib_installation_path>

> python3 setup.py lib

> pip3 install .

Clean build:
> python3 setup.py clean

Usage:
> python3 -m pyoccam1dcsem.occamfile

generates a simple RUNFILE

> python3 -m pyoccam1dcsem.dipole

runs forward model using RUNFILE
