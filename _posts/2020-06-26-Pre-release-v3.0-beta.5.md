---
layout: post
title: "Pre-release v3.0 beta 5"
date: 2020-06-26
categories: news
author: "Cris Luengo"
---

Since last week, it is possible to install the *DIPlib* and its Python bindings though PyPI,
see [here](https://pypi.org/project/diplib/). With a simple

    pip install diplib

one can immediately start using *DIPlib* from within Python, compiling from source no longer needed!
To get started using *DIPlib* in Python, see the very short [User Manual](/diplib-docs/pydip_user_manual.html)
and the [examples](https://github.com/DIPlib/diplib/tree/master/examples/python). Yes, we need more documentation.

We support:

- Windows, Python versions 3.7 and 3.8.
- macOS, Python versions 3.7 and 3.8.
- Linux, Python versions 3.6, 3.7 and 3.8.

If you use a different platform or a different version of Python, you will need to build from source.
This is not complicated. We have [simple and clear instructions available](https://github.com/DIPlib/diplib/blob/master/INSTALL.md).

We don't yet have a simple way of generating the *DIPimage* distribution (MATLAB toolbox), so building
from source is still necessary there.

To use the C++ library, we recommend that you build from source even if binary distributions were available.

[Changes in *DIPlib* as compared to version 2.9](/changelogs/diplib_3.0b5.html)  
[Changes in *DIPimage* as compared to version 2.9](/changelogs/dipimage_3.0b5.html)
