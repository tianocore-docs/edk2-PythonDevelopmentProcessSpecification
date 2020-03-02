<!--- @file
  introduction.md for Python Development Process and Coding Specification

  Copyright (c) 2020, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->
# 1 Introduction

This specification defines a set of python coding standards, development flow,
and tools to help to identify and fix deviations in written code.
These standards, flow and tools to establish
*	Uniformity of style
*	Uniform conventions
*	To maintain consistency
*	To maintain extensibility
*	To improve readability 
*	To improve maintainability, reusability

These rules apply to all code developed in Python for inclusion in the EDK II , 
and are intended as an enabling philosophy. All changes or additions 
from this point on shall conform to this specification. Pre-existing code does
not need to be updated for the sole purpose of conforming to this specification.
As conforming updates are made, the developer may update other content within
the modified file to bring it within compliance with this specification. 
This specification addresses the chronic problem of providing accurate
documentation of the code base by embedding the documentation within the code. 
A document generation system, using inbuilt python module, then produce 
formatted documentation by extracting information from specially formatted 
comment blocks and the syntactic elements of the code.
