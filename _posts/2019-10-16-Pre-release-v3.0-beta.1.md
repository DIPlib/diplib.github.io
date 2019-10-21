---
layout: post
title: "Pre-release v3.0-beta.1"
date: 2019-10-16
categories: news
author: "Ronald Ligteringen"
---

This is the **first** pre-release of the complete rewrite of *DIPlib* in C++. Most notably starting with this release the code is now open-source and has interfaces to *MATLAB* **and** *Python*. Binary distributions will be provided for Windows, macOS and Linux. Also instructions on how to build *DIPlib* yourself are available. Please read more on the [`README.md`](https://github.com/DIPlib/diplib/blob/master/README.md) of this repository and the website <https://diplib.github.io/diplib-docs/>.

*DIPlib* will be supported by *MATLAB* R2017a and higher (**not** R2018a) and Python 3.5, 3.6 and 3.7.

We would love to receive your feedback on this beta and invite you to use the [Issues tracker](https://github.com/DIPlib/diplib/issues).

16 October 2019: Windows binaries are included. They have been tested in Windows 7 and Windows 10 (64-bit). One version for *MATLAB* R2017a and R2017b `DIPlib3_installer_2017a.exe` and one version for *MATLAB* R2018b and higher `DIPlib3_installer_2018b.exe`. Note that the *MATLAB* interface of *DIPlib* cannot be used with *MATLAB* R2018a! Make sure you install the [Visual C++ Redistributable for Visual Studio 2019](https://aka.ms/vs/16/release/VC_redist.x64.exe) before using *DIPlib* in Windows. 

Binaries for macOS and Linux will be available soon!

See [the changes in *DIPlib* as compared to version 2.9](/changelogs/diplib_3.0.beta.html) and
[the changes in *DIPimage* as compared to version 2.9](/changelogs/dipimage_3.0.beta.html).
