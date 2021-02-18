---
layout: default
author: "Cris Luengo"
---

The purpose of the *DIPlib* project is to provide a one-stop library and
development environment for quantitative image analysis, be it applied
to microscopy, radiology, astronomy, or anything in between.

The *DIPlib* project contains the following modules:

- [*DIPlib*](/DIPlib.html), a C++ library for quantitative image analysis.

- [*DIPimage*](/DIPimage.html), a MATLAB toolbox for quantitative image analysis, built on *DIPlib*.
It is a mature toolbox, and offers much more than access to *DIPlib* from within MATLAB. It includes
a GUI and an interactive image display that can be used to explore 1D, 2D, 3D and 4D images.

- [*PyDIP*](/PyDIP.html), Python bindings to *DIPlib*.
This is currently a thin wrapper that exposes the C++ functionality with little change.

- [*DIPviewer*](/diplib-docs/viewer.html), an interactive image display
utility. It is usable from C++, Python and MATLAB programs. Within *DIPimage* this is an optional
alternative to the default MATLAB-native interactive display utility.

- [*DIPjavaio*](/diplib-docs/dipjavaio.html), an interface to
[*OME Bio-Formats*](https://www.openmicroscopy.org/bio-formats/), a Java-based library that reads
hundreds of image file formats. This module is usable from C++ and Python. *DIPimage* has a different
way of interfacing with *Bio-Formats*.

You will find the documentation and other useful links on the side-bar of this page.

---

## News

<ul>
{% for post in site.posts limit:3 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a>
  ({{ post.date | date: "%d %B %Y" }})</li>
{% endfor %}
</ul>

[All news](./news.html)


## Contributing

If you want to contribute to the *DIPlib* project, there are many different
ways of doing so:

- Write new algorithms. If you have an algorithm that you'd like to contribute
  to the project, we'll be happy to see it!

- Create an interface to another library or scripting language.

- Create tutorials for how to use *DIPlib*, *DIPimage* and/or *PyDIP*.

- Fix bugs or improve documentation.

- Add code to the unit tests.

- Create a logo for the project.

In any of these cases, see [`CONTRIBUTING.md`](https://github.com/DIPlib/diplib/blob/master/CONTRIBUTING.md)
to learn how to make optimal use of your time.
Don't be offended if you receive requests for modifications before your work is merged
with the project.

Your documentation and code contributions will carry the same licencing terms as the rest
of the library, you keep the copyright to any substantial contribution.
