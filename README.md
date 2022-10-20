PSBouncyCastle (v1.9.0)
==================

**PSBouncyCastle** is a PowerShell module that allows you to use the
crypto functionality from the [Legion of the BouncyCastle](http://www.bouncycastle.org/)
.NET libraries.

Currently it covers the X509 certificate functionality, in particular
allowing you to replace `makecert.exe` (from the Windows SDK) with
native PowerShell cmdlets.

This was written by *RLipscome* and forked to the current version in order to update the Crypto library.

Original Source (GitHub)
--

[GitHub - rlipscombe/PSBouncyCastle: PowerShell module for X509 certificates, using BouncyCastle](https://github.com/rlipscombe/PSBouncyCastle)

----

10/20/2022
Updated to latest binary distribution of Bounce Castle v1.9.0
Greg Jewett (GitHub: @jewettg)

* I am afraid I do not know how to generate nuspec or nupkg files, so those have been omitted.  
* BouncyCastle binary (DLL) v1.9.0 updated.
* Updated PSBouncyCastle.psm1; lines 7-8 to reference new binary version.
