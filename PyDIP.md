---
layout: default
title: PyDIP
author: "Cris Luengo"
---

<h1><i>PyDIP</i></h1>

Currently, *PyDIP* is a thin wrapper that makes most of the functionality in *DIPlib*
accessible from within Python.
Function names and arguments are mostly identical to the C++ functions. The only
exception is for indexing into images, which uses the Python slicing syntax.
Image objects created by the interface expose their data buffer, and so can be
used with most *NumPy* functions. Likewise, any object that exposes a data buffer
(e.g. *NumPy* arrays) can be used as input to *PyDIP* functions.

The interface only has automatically generated docstrings that show the names of
each of the parameters. Use the DIPlib reference to learn how to use each function.
Get started by reading [the *PyDIP* User Manual](https://diplib.github.io/diplib-docs/pydip_user_manual.html).

Images can be shown using the `Show` method, which uses *matplotlib*.
The `PyDIP.PyDIPviewer` sub-module gives access to [*DIPviewer*](https://diplib.github.io/diplib-docs/group__viewer.html).
When Python is started through the `examples/python/pydip.py` script, the `Show` function
will use the *DIPviewer* interactive display.

The [`/examples/python`](https://github.com/DIPlib/diplib/blob/master/examples/python/)
directory contains a few Jupyter notebooks that introduce the package and demonstrate
some of its functionality.
