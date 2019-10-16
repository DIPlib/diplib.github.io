---
layout: post
title: "Pre-release v3.0-beta.1"
date: 2019-10-16
categories: release
author: "Ronald Ligteringen"
---

This is the first pre-release of the complete rewrite of DIPlib (and DIPimage) in C++.
Most notably starting with this release the code is now open-source and has interfaces
to Matlab and Python. Binary distributions will be provided for Windows, macOS and Linux.
Also instructions on how to build DIPlib yourself are available. Please read more on the
README.md of this repository and the website https://diplib.github.io/diplib-docs/.

DIPlib will be supported by Matlab R2017a and higher (not R2018a) and Python 3.5, 3.6 and 3.7.

We would love to receive your feedback on this beta and invite you to use the Issues service.

16 October 2019: Windows binaries are included. They have been tested in Windows 7 and Windows 10 (64-bit). 
One version for Matlab R2017a and R2017b: `DIPlib3_installer_2017a.exe`, and one version for Matlab R2018b
and higher: `DIPlib3_installer_2018b.exe`. Note that the Matlab interface of DIPlib cannot be used with
Matlab R2018a! Make sure you install the Visual C++ Redistributable for Visual Studio 2019 before using
DIPlib on Windows.

Binaries for macOS and Linux will be available soon!

See [the changes from DIPlib 2 and DIPimage 2](/changelogs/3.0.beta-1.html).
