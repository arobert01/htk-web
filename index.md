---
title: "Getting started with the Helper ToolKit"
keywords: sample homepage
last_updated: September 19, 2019
tags: [getting_started]
sidebar: home_sidebar
permalink: index.html
summary: These brief instructions will help you get started quickly with the HTK
---

Introduction
============

HTK is an open-source software system that will help developers
of C++, VTK, OpenCV, ITK,... to develop faster. This library lists
common functions that can be easily use without redevelop it every times.


Reporting Bugs
==============

If you found an issue or a bug, please report it in the HTK tracker


Requirements
============

You have the possibility to use only some of the available libs by checking
CMake entries :
- Common : Common functionalities related to C++ (HTK_USE_COMMON)
- VTK : Functionalities related to VTK (HTK_USE_VTK)

If you want to use a lib which uses an external lib (like VTK), you have to
previously have a built lib on your computer. There is no superbuild.

Contributing
============

See [CONTRIBUTING.md](htk_contributing.html) for instructions to contribute.

License
===========

See [LICENSE](htk_license.html) for the license copyrights

{% include links.html %}
