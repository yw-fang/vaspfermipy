#######################################################################
VaspFermipy: A Python toolset for Fermi surface calculations in DFT (VASP)
#######################################################################

=============
Introduction
=============

VaspFermipy is aimed to be a python toolset for calculating and visualizing the
Fermi surface in Density Functional Theory (DFT) calculations. At present,
only VASP is supported.

=============
Installation
=============

- Step 1: install fermipy to your virtual environment

To install fermipy, use

 $ pip install fermipy

or

 $ git clone https://github.com/yw-fang/fermipy.git

 $ cd fermipy

 $ python setup.py install



=============
Usage
=============

- Generate KPOINTS with *k*-mesh of 3 * 4 * 5

 $ genk_fs -k 3 4 5

or

 $ genk_fs --kmesh 3 4 5

=============
License
=============

MIT LICENSE. See LICENSE file for more details.

=============
Author
=============

Yue-Wen FANG
