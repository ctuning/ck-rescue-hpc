CK repository for ResCuE workshop series
========================================

[![compatibility](https://github.com/ctuning/ck-guide-images/blob/master/ck-compatible.svg)](https://github.com/ctuning/ck)
[![automation](https://github.com/ctuning/ck-guide-images/blob/master/ck-artifact-automated-and-reusable.svg)](http://cTuning.org/ae)
[![workflow](https://github.com/ctuning/ck-guide-images/blob/master/ck-workflow.svg)](http://cKnowledge.org)

[![DOI](https://zenodo.org/badge/131708690.svg)](https://zenodo.org/badge/latestdoi/131708690)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

Prerequisites
=============
* [Collective Knowledge Framework](http://github.com/ctuning/ck)

Description
===========

CK web front-end templates, styles and images.

Usage:

 > ck pull repo:ck-rescue-hpc

 (dependency on ck-web repo will be automatically resolved)

 > ck start web

 > Open web page: http://localhost:3344/?template=rescue-hpc-workshop&page=index

 That's all.

Note, that it is possible to create a static website
(as we use at http://adapt-workshop.org)

Just go to script/compile-website-rescue-hpc-workshop
and run on Linux:
 > ./create_website.sh

or on Windows:
 > create_website.bat

This will create static html pages in tmp-website sub-directory
that you can upload to your web server.
