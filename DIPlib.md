---
layout: default
title: DIPlib
author: "Cris Luengo"
---

# *DIPlib*

*DIPlib* is an extensive C++ library for quantitative image analysis. It has
hundreds of algorithms for manipulating, filtering, segemeting and quantifying
images. There currently are more than 3000 documented symbols.

There are other image processing/analysis libraries available, some of
them hugely popular. Why do we keep investing time in developing and
improving *DIPlib*? The short answer is that we believe *DIPlib* offers
things that are not available elsewhere. The library is built on the
following three principles:

1. **Precision**

    We implement the most precise known methods, and output often defaults to
    floating-point samples. The purpose of these algorithms is quantification,
    not approximation.

2. **Ease of use**

    We use modern C++ features to provide a simple and intuitive interface
    to algorithms, with expressive syntax, default values, and little
    boiler-plate code required from the user. There is no need to be aware of
    an image's data type to use the algorithms effectively.

    Furthermore, developing an image analysis program involves a lot of trial-and-error,
    rapid prototyping approaches are applicable: the edit-compile-run loop
    should be quick. We aim for short compile times with pre-compiled algorithms
    and few public templates.

3. **Efficiency**

    We implement the most efficient known algorithms, as long as they don't
    compromise precision. Ease-of-use features might also incur a slight overhead
    in execution times. The library can be used in high-throughput quantitative analysis
    pipelines, but is not designed for real-time video processing.

Algorithms in *DIPlib* typically accept input images of any data type (though,
of course, some algorithms are specific to binary images, or cannot handle
complex images, etc.) and any number of dimensions (algorithms that are limited to
one specific dimensionality typically show so in their name). The image data
type and dimensionality do not need to be known at compile time. Images can
have pixels that are vectors or matrices, for some examples on how this
relates to the three points above, see "[Why tensors?](/diplib-docs/why_tensors.html)".

There are many other unique things about *DIPlib*, we encourage you to explore
[the documentation](/diplib-docs/index.html) to learn more about it.

See also the [`examples/`](https://github.com/DIPlib/diplib/tree/master/examples)
directory for a series of simple C++ programs that demonstrate how to use
various features of the library.

## Modules

Besides *MATLAB* and *Python* bindings, *DIPlib 3* currently has interfaces to the
following packages:

- *Bio-Formats*: *DIPjavaio* is an interface to Java-based image readers.
  It is designed to allow *DIPlib* to read hundreds of image file formats through
  [*OME Bio-Formats*](https://www.openmicroscopy.org/bio-formats/),
  but is generic enough to be used with other Java libraries as well.

- *OpenCV*: a single header file provides copyless conversion to and from
  [*OpenCV*](https://opencv.org) images, for *OpenCV* version 2 and newer.

- *Vigra*: a single header file provides copyless conversion to and from
  [*Vigra*](http://ukoethe.github.io/vigra/) images.

The *DIPlib* project also contains *DIPviewer*, an interactive image display utility.

## Installation

We recommend that you build the library yourself from sources. There are some optional
external dependencies, all required dependencies are included in the repository.
For build instructions see [`INSTALL.md`](https://github.com/DIPlib/diplib/blob/master/INSTALL.md).
