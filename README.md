ANEXIA Debian Packages
======================

This repository contains customized Debian packages built and
used by [ANEXIA](http://www.anexia-it.com).

The repository contains one directory per Debian codename at the top level,
followed by one directory per package at the secondary level.

At the third level at least a sources directory exists, whereas an additional
bin directory may exist.

The source directory contains everything required to build a package.
The bin directory, if it exists, contains pre-built packages.

Note
----

Due to a misunderstanding and a bad choice of the versioning scheme 
old packages with a version number ending in +anexia-shellshock0
appear to dpkg to be newer than their successor packages ending in
+anexia1. 
We are sorry if this caused any inconvenience and want to assure that
packages ending in +anexia1 are actually the newer versions.
Future packages will keep this versioning scheme and be released as +anexiaX,
whereas X denotes our patch level/package version.
