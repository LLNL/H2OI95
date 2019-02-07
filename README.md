# H2OI95
A Code for Evaluating the IAPWS-95 Equation-of-State Model for Water

This software evaluates the IAPWS-95 equation-of-state model of
Wagner and Pruss (2002) as described (and partially modified) by
IAPWS (2016). In addition to the usual outputs, thermochemical
functions are evaluated consistent with the CODATA recommendations
(Cox et al., 1989). This code is intended to run in a Windows command
line environment. The source code is written in "simple" Fortran,
using explicit variable typing, and passing information between
routines using only calling sequences (no common blocks).

This github repository is intended to contain completed distribution
packages for Windows PCs.

This ReadMe file applies to the github repository for this code.
It is provided with both .md and .txt extensions. The use of the .md
extension is a github thing, but this is not convenient on Windows
PCs.

The first version of of the software is:

  Version 1.0, Build 64
  Written by Thomas J. Wolery (wolery1@llnl.gov)
  Unclassified/Open Source Distribution
  LLNL-CODE-764398
  CP Numbber: CP02139

Copyright (c) 2018, Lawrence Livermore National Security, LLC
All rights reserved.

SPDX-License-Identifier: BSD-3-Clause

The first version distribution package is in the file H2OI95_v1_b64.zip.
Users should download this file.

The distribution package includes a Windows PC executable, along with
files to assist running it in a command window environment. The software
is run by providing a text-based input file, of which about 30 examples
are included in a test case library. Archived output files are also
included to assist in checking installation and any porting. A fuller
description is given in the associated report (Wolery, 2018). A PDF of
the report (LLNL-TR-761227) is included in the software distribution
package. References cited above are included in this report.

As written, H2OI95 v. 1.0, Build 64 is a "research" code designed to
support numerical studies of requisite iterative calculations. It has
been extensively tested in this regard. See the associated report (Wolery,
2018, LLNL-TR-761227). It is not optimized for speed.

There is no installation program. For installation instructions, see the
ReadMe.md or ReadMe.txt file in the distribution package.

------------------------------------------------------------------------
