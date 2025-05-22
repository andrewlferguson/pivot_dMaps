# pivot_dMaps
Python implementation of streaming pivot diffusion maps

Implementation of pivot diffusion maps algorithm [10.1021/acs.macromol.7b01684] variant of nonlinear manifold learning diffusion maps technique [10.1016/j.acha.2006.04.006]. Supports streaming analysis from hdf5 for analysis of very large data sets. Permits various normalizations of the diffusion kernel [10.1016/j.acha.2005.07.004]. Provision for Nyström extension for out-of-sample embedding of new data points.

Example application to Swiss Roll data set.

Python libraries required: numpy, scipy, matplotlib, sklearn, h5py
