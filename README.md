Cygwin h5py
===================

The files required to make a Cygwin package (32 and 64 bit) for the h5py package

Building and Testing under Cygwin
-----------

  * Download the Cygwin installer (either 32 or 64 bit, or both) from Cygwin.com
  * Install all necessary dependencies (listed under DEPEND in the .cygport files): python, numpy, hdf5, etc
  * Use git to clone this repo: "git clone https://url_to_repo/"
  * Use cygport to download the Python package: "cygport python-h5py.cygport download"
  * Build and package it: "cygport python-h5py.cygport all"
  * Test the new package: "cygport python-h5py.cygport test"
  * The Cygwin packages and setup.hint file will be under the python-h5py-X.Y.Z/dist directory
