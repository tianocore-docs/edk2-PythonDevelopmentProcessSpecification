<!--- @file
  python_coding_guidelines_and_tools.md for Python Development Process and Coding Standards Specification

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


# **2 Python coding guidelines and tools:** {#python-coding-guidelines-and-tools}

This section covers python coding style guidelines followed.

###	PEP 8- Style guide for python code: 
`PEP8` covers python code style guide and helps to maintain consistency in code. A style guide is about consistency. Consistency within a project or module or function is most important. Complete specification available at 
https://www.python.org/dev/peps/pep-0008/
 
###	PEP 257- Docstring Conventions: 
`PEP257` covers semantics and conventions associated with python docstrings. The aim of `PEP257` to standardize the high-level structure of docstrings. Complete specification available at https://www.python.org/dev/peps/pep-0257/

###	PEP 484- Type Hints: 
`PEP484` introduces a provisional module to provide the standard definitions and tools, along with some conventions for situations where annotations are not available. More details on PEP484 available at
https://www.python.org/dev/peps/pep-0484/



###   **Falke8:** 
`Flake8` is a Python library wrapper around `PyFlakes, pycodestyle` and Ned Batchelder’s `McCabe` script<br>
  __PyFlakes:__

  *    A simple program that checks Python source files for errors.
  *    It is available on PyPI [https://pypi.org/project/pyflakes/](https://pypi.org/project/pyflakes/)

__Pydcodestyle:__

  *    `Pycodestyle` used to called pep8 is a tool to check your Python code against some of    the style conventions in PEP8.
  *    It is available on PyPI [https://pypi.org/project/pycodestyle/](https://pypi.org/project/pycodestyle/)

__McCabe:__

  *    Ned’s script to check for the `McCabe` complexity for Python code.
  *    It is available on PyPI [https://pypi.org/project/mccabe/](https://pypi.org/project/mccabe/)

###   **pytest:**

It is important to validate the classes, methods, and functions we write. This will help to miniate the core software functionality of the modules. This is possible by writing a unit test which is the first level of software functionality validation. The `pytest` framework helps to write small test, yet scales to support complex functional testing for applications and libraries.

Complete features and documentation available at:  [https://docs.pytest.org/en/latest/contents.html](https://docs.pytest.org/en/latest/contents.html)

###   **mypy**:

The `mypy` tool aims to combine the benefits of dynamic and static typing. `mypy` combines a powerful type system and compile-time type checking. It is an optional static type checker for python. `Mypy` type checks standard Python programs; run them using any Python VM with basically no runtime overhead. More details available at
[https://mypy.readthedocs.io/en/stable/](https://mypy.readthedocs.io/en/stable/)

        
    