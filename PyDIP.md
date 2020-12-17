---
layout: default
title: PyDIP
author: "Cris Luengo"
---

# *PyDIP*

Currently, *PyDIP* is a thin wrapper that makes most of the functionality in *DIPlib*
accessible from within Python.
Function names and arguments are mostly identical to the C++ functions. The only
exception is for indexing into images, which uses the Python slicing syntax.
Image objects created by the interface expose their data buffer, and so can be
used with most *NumPy* functions. Likewise, any object that exposes a data buffer
(e.g. *NumPy* arrays) can be used as input to *PyDIP* functions.

The interface only has automatically generated docstrings that show the names of
each of the parameters. Use the DIPlib reference to learn how to use each function.
Get started by reading [the *PyDIP* User Manual](/diplib-docs/pydip_user_manual.html).

Images can be shown using the `Show` method, which uses *matplotlib*.
The `PyDIP.PyDIPviewer` sub-module gives access to [*DIPviewer*](/diplib-docs/group__viewer.html).
When Python is started through the `examples/python/pydip.py` script, the `Show` function
will use the *DIPviewer* interactive display.

These Jupyter notebooks give a short introduction:

- [pydip_basics.ipynb](https://github.com/DIPlib/diplib/blob/master/examples/python/pydip_basics.ipynb)
- [tensor_images.ipynb](https://github.com/DIPlib/diplib/blob/master/examples/python/tensor_images.ipynb)


## Installation

To install, simply type

    pip install diplib

Windows users might need to install the
[Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads).
To read images through the *Bio-Formats* library, you will need to download it
separately:

    python -m diplib download_bioformats
