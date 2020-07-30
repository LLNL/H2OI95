# H2OI95
A Code for Evaluating the IAPWS-95 Equation-of-State Model for Water

This software evaluates the IAPWS-95 equation-of-state model of Wagner and Pruss (2002) as described (and partially modified) by IAPWS (2016). Thermochemical functions are evaluated consistent with the CODATA recommendations (Cox et al., 1989). Version 1.1 adds evaluation of supplemental IAPWS-sanctioned models for additional properties including viscosity and dielectric constant. A bug affecting some properties near the critical point was fixed. This code is intended to run in a Windows command line environment. The source code is written in "simple" FORTRAN, using explicit variable typing, and passing information between routines using only calling sequences (no common blocks).

The latest version of the software is:

Version 1.1, Build 118. Written by Thomas J. Wolery (wolery1@llnl.gov) Unclassified/Open Source Distribution LLNL-CODE-811146, CP Number: CP022321,

Copyright (c) 2018,2020 Lawrence Livermore National Security, LLC All rights reserved.

SPDX-License-Identifier: BSD-3-Clause

The latest version distribution package is in the file H2OI95_v1.1_b118.zip. Users should download this file.

The distribution package includes a Windows PC executable, along with files to assist running it in a command window environment. The software is run by providing a text-based input file, of which about 30 examples are included in a test case library. Archived output files are included to assist in checking installation and any porting. A full description is given in the associated report (Wolery, 2020). A PDF of the report (LLNL-TR-805304) is included in the distribution package. References cited above are included in this report.

As currently written, H2OI95 is a "research" code. It is not optimized for speed.

There is no installation program. For installation instructions, see the ReadMe.md or ReadMe.txt file included in the distribution package

------------------------------------------------------------------------
