---
layout: post
title: "New version without SCIL"
date: 2004-06-29
categories: news
author: "Ronald Ligteringen"
---

A new version of DIPlib and DIPimage has been released for the SunOS, Linux, MacOS X and Windows platforms.
Besides the usual small bug fixes and improvements, we added, among others, the following features:
new filters (bilateral filtering, adaptive filtering, diffusion, normalized convolution, hysteresis threshold),
granulometries, improved image display (looking glass, custom color look-up tables), and improved file I/O
(reading Zeiss LSM files, reading file properties and physical distance between pixels, reading time series, etc.).

Notice to SCIL_Image users: we are dropping support for the SCIL interface, and will no longer be distributing it.
Do not upgrade DIPlib if you want to keep using it under SCIL.
