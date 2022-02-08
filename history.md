---
layout: default
title: "A short history"
author: "Cris Luengo"
---

# A short history

Development of *DIPlib* started in 1995, at the capable hands of
Geert van Kempen and Michael van Ginkel, under direction of
Lucas van Vliet, at the Pattern Recognition Group (later Quantitative
Imaging, now Computational imaging) of
[Delft University of Technology (TU Delft)](https://www.tudelft.nl/en/).
Most of the algorithms that had been developed there were included in the
library, together with a large collection of standard algorithms.
Due to the lack of a C++ standard at the time, they developed the library
in C, recreating much of the C++ functionality (templates,
function overloading, exceptions, data hiding, memory management)
using preprocessor macros and other tricks.
*DIPlib* was originally used on HPUX, Solaris and IRIX, and later on
Windows, Linux, Mac OS 9 and Mac OS X.

Originally, the *DIPlib* library was used from within the *SCIL_Image*
image processing software. In 1999, Cris Luengo (with a lot of help from
Michael van Ginkel) wrote an interface to *MATLAB*, defining a flexible
and intuitive command-line syntax for the development of image analysis
algorithms. That same year, a user-friendly GUI in the spirit of
*SCIL_Image* was written, as well as interactive image display tools. This
*MATLAB* toolbox, called *DIPimage*, became the primary interface to the
*DIPlib* library.

*DIPlib 3* represents the first major rewrite of the *DIPlib* code base.
Planning started in 2014, and by 2017 Cris Luengo had rewritten the infrastructure
in C++14, using all the original ideas and concepts, but adding tensor images,
color support, and other ideas we had developed within the *DIPimage* toolbox.
C++14 allows the user to write code that is almost as short as the equivalent
*MATLAB* code, making it simple to use the library even for rapid prototyping.
The new infrastructure is much easier to read, maintain, and contribute to.
The original intention was to make minimal changes to the image analysis
routines so that they would work within the new infrastructure, but we ended up
significantly rewriting many of those routines, and some were rewritten from
scratch to use more efficient algorithms underneath.
Bernd Rieger provided financial support  for some of this effort through
a European Research Council grant.
[Very few routines have not been ported yet.](https://github.com/DIPlib/diplib/issues/20)

The *DIPimage* toolbox has been updated to optimally use *DIPlib 3*. This means
that some of the *MATLAB* code was replaced with calls to *DIPlib*, and
the low-level interface (`dip_*` functions) disappeared. The internal
representation of images has also changed. However, we strove
to keep backwards-compatibility in the high-level toolbox functions.
[Some functions have not yet been ported over.](https://github.com/DIPlib/diplib/issues/21)

With financial support from Flagship Biosciences, Cris Luengo created the
initial Python bindings (*PyDIP*) in 2017.

Wouter Caarls created the *DIPviewer* and *DIPjavaio* components
in 2017 and 2019, respectively.

See [*DIPlib* contributors](/contributors.html) for a list of people that
contributed code to the project.
