ITKSmoothingRecursiveYvvGaussianFilter
======================================

.. image:: https://github.com/InsightSoftwareConsortium/ITKSmoothingRecursiveYvvGaussianFilter/workflows/Build,%20test,%20package/badge.svg


Overview
--------

This is a module for the `Insight Toolkit (ITK) <https://itk.org>`_ that
implements the Young & Van Vliet recursive Gaussian smoothing filter for GPU
(OpenCL) and CPU.

For more information, see the `Insight Journal article <https://hdl.handle.net/10380/3425>`_::

  Vidal-Migallon I., Commowick O., Pennec X., Dauguet J., Vercauteren T.
  GPU and CPU implementation of Young - Van Vliet's Recursive Gaussian Smoothing Filter
  The Insight Journal. January-December. 2013.
  https://hdl.handle.net/10380/3425
  https://www.insight-journal.org/browse/publication/896


Installation
------------

If you would like to test the GPU smoothing filter, make sure to check the
flag `ITK_USE_GPU` during configuration and to provide a path to a valid
OpenCL installation (libraries and include directories). To do this you may
have to toggle advanced mode on CMake.

Install Python packages with::

  pip install itk-smoothingrecursiveyvvgaussianfilter

License
-------

This software is distributed under the Apache 2.0 license. Please see
the *LICENSE* file for details.
