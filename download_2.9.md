---
layout: default
title: "Download DIPlib and DIPimage 2.9"
author: "Cris Luengo"
---

# Download *DIPlib* and *DIPimage* version 2.9

Version 2.9 of *DIPlib* and *DIPimage* is no longer supported, but is still available though this page.

The links below can be used to obtain a non-commercial license. This license is free, and can be used
by students and staff in a University research project *without* an industrial sponsor.
If you need to obtain the commercial license for version 2.9 or older of *DIPlib* and *DIPimage*,
please contact <license@diplib.org>.
This version is not open source. Version 3 of the library and toolbox are open source.

You may download and use *DIPimage* and *DIPlib* after complying with the following three terms of use:

1. I agree to all terms in the [license agreement](#license).
1. I declare I will use *DIPimage* or *DIPlib* only for non-commercial purposes.
1. I declare I will not redistribute any of this software.

## Compatibility

Version 2.9 of *DIPimage* is compatible with MATLAB R2008a and up. This version will not run on older
versions of MATLAB!

- On MacOS, this version of *DIPimage* is compatible only with MATLAB R2009bSP1 and up.
- MATLAB R2015b has a "feature" which results in an error with some *DIPimage* functions
   (e.g. read color images). This "feature" has been resolved in version R2016a.
   In other words: do **not** use MATLAB R2015b with *DIPimage*.
- Starting this version, 32-bit Windows is no longer supported. For 32-bit Windows support please
[download an older version](#older-releases).

All versions have been tested on the following platforms:

| version         | tested on                                 | created with                     |
+-----------------|-------------------------------------------|----------------------------------|
| Linux 32-bits   | Ubuntu 14.04.1 32-bits MATLAB 2008a       | Ubuntu 14.04.1 32-bits GCC 4.8.2 |
|                 | Ubuntu 14.04.1 32-bits MATLAB 2012a       |                                  |
| Linux 64-bits   | Ubuntu 14.04.1 64-bits MATLAB 2008a       | Ubuntu 14.04.1 64-bits GCC 4.8.2 |
|                 | Ubuntu 14.04.1 64-bits MATLAB 2016a       |                                  |
| MacOS X         | MacOS X 10.10 MATLAB 2009bSP1             | MacOS X 10.10 GCC 4.9.1          |
|                 | MacOS X 10.10 MATLAB 2016a                |                                  |
| Windows 64-bits | Windows 2008 64-bits MATLAB 2008a 64-bits | Windows 2008 64-bits VS 2012     |
|                 | Windows 2008 64-bits MATLAB 2016a 64-bits |                                  |

## Download

Please make sure you follow the installation instructions found in
[the DIPimage User Manual](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/dipimage_user_manual.pdf).

- For Linux 32-bits: [dipimage_2.9_lin32.tbz](https://ftp.imphys.tudelft.nl/DIPimage/2.9/dipimage_2.9_lin32.tbz).
- For Linux 64-bits: [dipimage_2.9_lin64.tbz](https://ftp.imphys.tudelft.nl/DIPimage/2.9/dipimage_2.9_lin64.tbz).
- For MacOS X (10.6 or higher): [dipimage_2.9_darwin.tbz](https://ftp.imphys.tudelft.nl/DIPimage/2.9/dipimage_2.9_darwin.tbz).
- For Windows 64-bits [DIPimage 2.9 installer win64.exe](https://ftp.imphys.tudelft.nl/DIPimage/2.9/DIPimage%202.9%20installer%20win64.exe)
    (recommended) or [dipimage_2.9_win64.zip](https://ftp.imphys.tudelft.nl/DIPimage/2.9/dipimage_2.9_win64.zip) (for manual installation).

The set of demo images can be downloaded in two forms:

- [images.tbz](https://ftp.imphys.tudelft.nl/DIPimage/images.tbz) or
- [images.zip](https://ftp.imphys.tudelft.nl/DIPimage/images.zip).

Both files contain the same files, so you only need to download one format.

*DIPimage* documentation:

- [User Manual (PDF)](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/dipimage_user_manual.pdf)
- [Introduction to *DIPimage* (PDF)](https://ftp.imphys.tudelft.nl/DIPimage/docs/Introduction_to_DIPimage.pdf)
- Function reference is available within the toolbox
- [MEX-file programming with *DIPimage* (PDF)](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/mex_file_programming.pdf)

*DIPlib* documentation:

- [Programmers Guide (PDF)](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/diplib_programmers_guide.pdf)
- [Function Reference (PDF)](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/diplib_reference_guide.pdf) (~3Mb)
- [Online Function Reference (HTML)](https://ftp.imphys.tudelft.nl/DIPimage/latest/docs/reference/)

*DIPlib* sample source code:

- [Sample stand-alone application in C](https://ftp.imphys.tudelft.nl/DIPimage/docs/standalone.c)
- [Same application without error-handling macros](https://ftp.imphys.tudelft.nl/DIPimage/docs/standalone2.c)
- [Demonstration of the measurement functions](https://ftp.imphys.tudelft.nl/DIPimage/docs/measuredemo.c)
- [Stand-alone application to create a thumbnail](https://ftp.imphys.tudelft.nl/DIPimage/docs/makethumbs.c)
   (this is a more complete and useful sample)

## Older releases

Throughout time support for older versions of MATLAB has been dropped. Older releases of *DIPimage* might
support these older versions. These can be found in their respective directories on our FTP site:
<https://ftp.imphys.tudelft.nl/DIPimage/>.

Also other older platforms have been supported in previous releases of *DIPlib* and *DIPimage*.
These can be found here: <https://ftp.imphys.tudelft.nl/DIPimage/unsupported>.

## License

The Computational Imaging Group of the TU Delft, to be called CI, has developed and is the owner of the
image processing library written in C and all related documentation known as *DIPlib*, hereafter called SOFTWARE.

CI also developed a MATLAB toolbox for image processing based on *DIPlib*, known as *DIPimage*.
*DIPimage* is freely available for *DIPlib* license holders and available for the following platforms:

- Linux 32-bit
- Linux 64-bit
- MacOS X 10.6 or higher (Intel)
- Windows XP 64-bit

as well as for some unsupported platforms, mostly for older versions of *DIPimage*:

- Windows 32-bit
- MacOS X (pre-intel)
- Solaris 8 or later
- Linux 2.2
- IRIX / IRIX64
- Alpha/OSF1

### 1. Licenses

1.1. Source code licenses of the SOFTWARE are not available.

1.2. Non-commercial license:

- **A** - A University license. This license is for non-commercial use by students and staff in a University
    research project *without* an industrial sponsor. Redistribution of SOFTWARE or parts thereof in any form
    is not permitted. This license is free.

1.3. Commercial licenses:

- **B1** - A single-user license. Price: 2500 Euro.
- **B2** - A group license. Up to 10 users in a single business unit. Price: 15000 Euro.
- **C** - A closed redistribution license. This license gives, in addition to the no-redistribution licenses (B),
    the permission to use and redistribute the *DIPlib* library included in a commercial product,
    provided that the *DIPlib* components are neither visible to nor directly accessible by the end-user.
    Price: on request.
- **D** - A full non-exclusive redistribution license. This terms of this license agreement cannot be in
    conflict with the other licenses (A, B, and C). Price: on request.

1.4. The commercial licenses for a non-supported computer platform may be provided on request.
There will be minimum surcharge of 500 Euro.

1.5. All prices listed are exclusive BTW (value added tax). BTW in the The Netherlands is 21%.

### 2. Upgrades and Support

2.1. All licenses are provided on an "as is" basis without support or guarantees.

2.2. All license holders are entitled to freely download upgrades of the the SOFTWARE as they become available,
up to a maximum of three years after the original purchase.

2.3. CI has the right to stop the development and distribution of the SOFTWARE at any time without prior notice
to the license holders.

### 3. Disclaimer

3.1. The CUSTOMER acknowledges that the SOFTWARE is a research tool and that it is being supplied 'as is',
without any accompanying services from CI.

3.2. CI makes no representations or warranties of any kind, either express or implied, as to any matter
whatsoever, including but not limited to implied warranties of merchantability or fitness for any particular purpose or that the use of the SOFTWARE will not infringe any patent or copyright.

3.3. The CUSTOMER agrees that CI shall not be held to any liability with respect to any claim by the
CUSTOMER or a third party arising from or on account of the use of the SOFTWARE or redistribution of
the SOFTWARE. CI shall not be liable for any special indirect, incidental or consequential damages
arising out of the licensed rights granted hereunder.

3.4. CI cannot be held to any liability with respect to errors in the SOFTWARE or damage caused by correct
or incorrect use of the SOFTWARE.

### 4. Copyrights

4.1. The SOFTWARE is build with several external libraries (gif, ics, jpeg, tiff and zlib).
The licenses of these libraries expressly permit the embedding in commercial and non-commercial applications.
They do require to mention the copyright with the application.
For each library, the copyright can be downloaded below:

- [gif license.txt](https://ftp.imphys.tudelft.nl/DIPimage/licenses/gif_license.txt)
- [ics license.txt](https://ftp.imphys.tudelft.nl/DIPimage/licenses/ics_license.txt)
- [jpeg license.txt](https://ftp.imphys.tudelft.nl/DIPimage/licenses/jpeg_license.txt)
- [tiff license.txt](https://ftp.imphys.tudelft.nl/DIPimage/licenses/tiff_license.txt)
- [zlib license.txt](https://ftp.imphys.tudelft.nl/DIPimage/licenses/zlib_license.txt)

### Request license

A University license (license A) can be obtained via the Download page.
You can then immediately download the software.

For other licenses (license B, C or D), please send an e-mail to <license@diplib.org>.
