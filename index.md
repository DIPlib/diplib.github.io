---
layout: default
author: "Cris Luengo"
---

**NOTE!** The DIPlib website is currently at [diplib.org](http://www.diplib.org).

---

Welcome to the web site of the DIPlib project. The project contains the following modules:

- [*DIPlib*](https://diplib.github.io/diplib-docs/), a C++ library for quantitative image analysis.
It has been in development at Delft University of Technology in The Netherlands since 1995.
The 3.0 release of *DIPlib* represents a complete rewrite in modern C++ of the library infrastructure,
with most of the image processing and analysis algorithms ported from the previous version,
and some of them improved significantly. Many of the improvements to *DIPlib* are a result of porting
over concepts and ideas first implemented in *DIPimage*.

- [*DIPimage*](/DIPimage.html), a MATLAB toolbox for quantitative image analysis, built on *DIPlib*.
It has been in development at Delft University of Technology in The Netherlands since 1999.

- [*PyDIP*](/PyDIP.html), Python bindings to *DIPlib*.
This is currently a thin wrapper that exposes the C++ functionality with little change.

- [*DIPviewer*](https://diplib.github.io/diplib-docs/group__viewer.html), an interactive image display
utility. It is usable from C++, Python and MATLAB programs. Within *DIPimage* this is an optional
alternative to the default MATLAB-native interactive display utility.

- [*DIPjavaio*](https://diplib.github.io/diplib-docs/group__javaio.html), an interface to
[*OME Bio-Formats*](https://www.openmicroscopy.org/bio-formats/), a Java-based library that reads
hundreds of image file formats. This module is usable from C++ and Python. *DIPimage* has a different
way of interfacing with *Bio-Formats*.

You will find the documentation and other useful links on the side-bar of this page.

---

<h2>News</h2>

<ul>
{% for post in site.posts limit:3 %}
  <li><a href="{{ post.url }}">{{ post.title }}</a>
  ({{ post.date | date: "%d %B %Y" }})</li>
{% endfor %}
</ul>

[All news](./news.html)


<h2>Contributing</h2>

If you want to contribute to the *DIPlib* project, there are many different
ways of doing so:

- Write new algorithms. If you have an algorithm that you'd like to contribute
  to the project, we'll be happy to see it!

- Create an interface to another library or scripting language.

- Create tutorials for how to use *DIPlib*, *DIPimage* and/or *PyDIP*.

- Fix bugs or improve documentation.

- Add code to the unit tests.

- Improve the markup of the documentation, or create a logo for the project.

In any of these cases, see <a href="https://github.com/DIPlib/diplib/blob/master/CONTRIBUTING.md">`CONTRIBUTING.md`</a>
to learn how to make optimal use of your time.
Don't be offended if you receive requests for modifications before your work is merged
with the project.

Your documentation and code contributions will carry the same licencing terms as the rest
of the library, you keep the copyright to any substantial contribution.


<h2>License</h2>

The *DIPlib* project is licensed under the Apache 2.0 license, see the
<a href="https://github.com/DIPlib/diplib/blob/master/README.md">`README.md`</a> file
in the root of the repository.

The Apache 2.0 license is a permissive open-source license. In short, this means that
you can use this software as you see fit, including making modifications, and distribute
this software, parts of it, and/or your modifications to it, either in source form or as
binaries. You are free to keep your modifications private, you are not required to
distribute sources with your binaries. HOWEVER, you must include proper attribution, as
well as the copyright notices, with any such distribution. You cannot pretend that you
wrote this software, and you cannot make it look like we endorse any software that you
wrote.

If you make modifications to this software, you are not required to share those with us,
but we certainly would appreciate any such contribution!

Note that this short description of the license does not replace the license text and
might not correctly represent all the legalese in the licence. Please read the actual
licence text if you plan to redistribute this software.
