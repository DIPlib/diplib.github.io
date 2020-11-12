---
layout: default
title: "Download DIPlib and DIPimage 2.9"
author: "Cris Luengo"
---

<h1>Download <i>DIPlib</i> and <i>DIPimage</i> version 2.9</h1>

Version 2.9 of *DIPlib* and *DIPimage* is no longer supported, but is still available though this page.

The links below can be used to obtain a non-commercial license. This license is free, and can be used by students
and staff in a University research project *without* an industrial sponsor. If you need to obtain the commercial
license for version 2.9 or older of *DIPlib* and *DIPimage*, please contact <a href="mailto:license@diplib.org">license@diplib.org</a>.
This version is not open source. Version 3 of the library and toolbox are open source.

You may download and use *DIPimage* and *DIPlib* after complying with the following three terms of use:
1. I agree to all terms in the [license agreement](#license).
2. I declare I will use *DIPimage* or *DIPlib* only for non-commercial purposes.
3. I declare I will not redistribute any of this software.

<h2>Compatibility</h2>

Version 2.9 of *DIPimage* is compatible with MATLAB R2008a and up. This version will not run on older versions of MATLAB!

- On MacOS, this version of *DIPimage* is compatible only with MATLAB R2009bSP1 and up.
- MATLAB R2015b has a "feature" which results in an error with some *DIPimage* functions (e.g. read color images). This
"feature" has been resolved in version R2016a. In other words: do **not** use MATLAB R2015b with *DIPimage*
- Starting this version, 32-bit Windows is no longer supported. For 32-bit Windows support please
[download an older version](#older).

All versions have been tested on the following platforms:

| version         | tested on                                 | created with                     |
+-----------------|-------------------------------------------|----------------------------------|
| Linux 32-bits   | Ubuntu 14.04.1 32-bits MATLAB 2008a       | Ubuntu 14.04.1 32-bits GCC 4.8.2 |
| &nbsp;          | Ubuntu 14.04.1 32-bits MATLAB 2012a       | &nbsp;                           |
| Linux 64-bits   | Ubuntu 14.04.1 64-bits MATLAB 2008a       | Ubuntu 14.04.1 64-bits GCC 4.8.2 |
| &nbsp;          | Ubuntu 14.04.1 64-bits MATLAB 2016a       | &nbsp;                           |
| MacOS X         | MacOS X 10.10 MATLAB 2009bSP1             | MacOS X 10.10 GCC 4.9.1          |
| &nbsp;          | MacOS X 10.10 MATLAB 2016a                | &nbsp;                           |
| Windows 64-bits | Windows 2008 64-bits MATLAB 2008a 64-bits | Windows 2008 64-bits VS 2012     |
| &nbsp;          | Windows 2008 64-bits MATLAB 2016a 64-bits | &nbsp;                           |


<h2>Download</h2>

- For Linux 32-bits: <a href="ftp://qiftp.tudelft.nl/DIPimage/2.9/dipimage_2.9_lin32.tbz" target="_blank">dipimage_2.9_lin32.tbz</a>.
- For Linux 64-bits: <a href="ftp://qiftp.tudelft.nl/DIPimage/2.9/dipimage_2.9_lin64.tbz" target="_blank">dipimage_2.9_lin64.tbz</a>.
- For MacOS X (10.6 or higher): <a href="ftp://qiftp.tudelft.nl/DIPimage/2.9/dipimage_2.9_darwin.tbz" target="_blank">dipimage_2.9_darwin.tbz</a>.
- For Windows 64-bits <a href="ftp://qiftp.tudelft.nl/DIPimage/2.9/DIPimage%202.9%20installer%20win64.exe" target="_blank">DIPimage 2.9 installer win64.exe</a>
  (recommended) or <a href="ftp://qiftp.tudelft.nl/DIPimage/2.9/dipimage_2.9_win64.zip" target="_blank">dipimage_2.9_win64.zip</a> (for manual installation).

The set of demo images can be downloaded in two forms: 
<a href="ftp://qiftp.tudelft.nl/DIPimage/images.tbz" target="_blank">images.tbz</a> or
<a href="ftp://qiftp.tudelft.nl/DIPimage/images.zip" target="_blank">images.zip</a>.
Both files contain the same files, so you only need to download one format.


<h2><a id="license"></a>Older releases</h2>

Throughout time support for older versions of MATLAB has been dropped. Older releases of *DIPimage* might support these older
versions. These can be found in their respective directories on our FTP site:
<a href="ftp://qiftp.tudelft.nl/DIPimage" target="_blank">ftp://qiftp.tudelft.nl/DIPimage</a>.

Also other older platforms have been supported in previous releases of *DIPlib* and *DIPimage*. These can be found here:
<a href="ftp://qiftp.tudelft.nl/DIPimage/unsupported" target="_blank">ftp://qiftp.tudelft.nl/DIPimage/unsupported</a>.


<h2><a id="license"></a>License</h2>

The Quantitative Imaging Group of the TU Delft, to be called QI, has developed and is the owner of the image
processing library written in C and all related documentation known as *DIPlib*, hereafter called SOFTWARE.

QI also developed a MATLAB toolbox for image processing based on *DIPlib*, known as *DIPimage*. *DIPimage* is
freely available for *DIPlib* license holders and available for the following platforms:
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

<h3>1. Licenses</h3>

1.1. Source code licenses of the SOFTWARE are not available.

1.2. Non-commercial license:
<ul>
  <li><b>A</b> - A University license. This license is for non-commercial use by students and staff in a University
    research project *without* an industrial sponsor. Redistribution of SOFTWARE or parts thereof in any form is not
    permitted. This license is free.</li>
</ul>

1.3. Commercial licenses:

<ul>
  <li><b>B1</b> - A single-user license. Price: 2500 Euro.</li>
  <li><b>B2</b> - A group license. Up to 10 users in a single business unit. Price: 15000 Euro.</li>
  <li><b>C</b> - A closed redistribution license. This license gives, in addition to the no-redistribution licenses (B),
    the permission to use and redistribute the *DIPlib* library included in a commercial product, provided that the
    *DIPlib* components are neither visible to nor directly accessible by the end-user. Price: on request.</li>
  <li><b>D</b> - A full non-exclusive redistribution license. This terms of this license agreement cannot be in conflict
    with the other licenses (A, B, and C). Price: on request.</li>
</ul>

1.4. The commercial licenses for a non-supported computer platform may be provided on request. There will be minimum
surcharge of 500 Euro.

1.5. All prices listed are exclusive BTW (value added tax). BTW in the The Netherlands is 21%.

<h3>2. Upgrades and Support</h3>

2.1. All licenses are provided on an "as is" basis without support or guarantees.

2.2. All license holders are entitled to freely download upgrades of the the SOFTWARE as they become available, 
up to a maximum of three years after the original purchase.

2.3. QI has the right to stop the development and distribution of the SOFTWARE at any time without prior notice
to the license holders.

<h3>3. Disclaimer</h3>

3.1. The CUSTOMER acknowledges that the SOFTWARE is a research tool and that it is being supplied 'as is',
without any accompanying services from QI.

3.2. QI makes no representations or warranties of any kind, either express or implied, as to any matter whatsoever,
including but not limited to implied warranties of merchantability or fitness for any particular purpose
or that the use of the SOFTWARE will not infringe any patent or copyright.

3.3. The CUSTOMER agrees that QI shall not be held to any liability with respect to any claim by the CUSTOMER
or a third party arising from or on account of the use of the SOFTWARE or redistribution of the SOFTWARE.
QI shall not be liable for any special indirect, incidental or consequential damages
arising out of the licensed rights granted hereunder.

3.4. QI cannot be held to any liability with respect to errors in the SOFTWARE or damage caused by correct
or incorrect use of the SOFTWARE.

<h3>4. Copyrights</h3>

4.1. The SOFTWARE is build with several external libraries (gif, ics, jpeg, tiff and zlib). 
The licenses of these libraries expressly permit the embedding in commercial and non-commercial applications.
They do require to mention the copyright with the application. 
For each library, the copyright can be downloaded below:
- <a href="ftp://qiftp.tudelft.nl/DIPimage/licenses/gif_license.txt" target="_blank">gif license.txt</a></li>
- <a href="ftp://qiftp.tudelft.nl/DIPimage/licenses/ics_license.txt" target="_blank">ics license.txt</a></li>
- <a href="ftp://qiftp.tudelft.nl/DIPimage/licenses/jpeg_license.txt" target="_blank">jpeg license.txt</a></li>
- <a href="ftp://qiftp.tudelft.nl//DIPimage/licenses/tiff_license.txt" target="_blank">tiff license.txt</a></li>
- <a href="ftp://qiftp.tudelft.nl/DIPimage/licenses/zlib_license.txt" target="_blank">zlib license.txt</a></li>

<h3>Request license</h3>

A University license (license A) can be obtained via the Download page. You can then immediately download the software.

For other licenses (license B, C or D), please send an e-mail to <a href="mailto:license@diplib.org">license@diplib.org</a>.

