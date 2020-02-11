<!--- @file
  development_steps_and_flowchard.md for Python Development Process and Coding Specification

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

# **3 Development steps and flowchart:** {#development-steps-and-flowchart}

*   Write code which follows PEP8, PEP257 and PEP484 recommendations
*   Run `flake8` on source code.
*   Run **`mypy`** for type hints checking of the code
*   Write unit tests using **`pytest`**
*   Run all unit tests.
*   Send review
*   Generate documents using `pydoc`
*   Write/modify/generate specifications wherever applicable

    Following flow chart explains complete development lifecycle.
    
{% plantuml %}
@startuml
start
repeat
repeat
  repeat
    :Source code;
  repeat while (Run flake8, mypy?) is (Errors)
    ->Pass;

repeat while (Run unit tests?) is (            Errors)
->Pass;
:     Code review,
Online documents;

repeat while (Run flake8,mypy,unitTests,
                  Logical issues?) is (         Errors)
->Pass;
:Submit;
:Update Online documents;

stop
@enduml
{% endplantuml %}



 