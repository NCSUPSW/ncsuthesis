--------------------------------------------------------------------
NC State LaTeX class and file templates.
E-mail: jmhykes@ncsu.edu
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
--------------------------------------------------------------------

The ncsuthesis class provides formatting, macros, and content
to meet the thesis requirements of North Carolina State University,
specifically the ETD guidelines.

This is the development repository. The archive useful for a student
writing their thesis can be built by executing

   build-release.py -v <version number>

in this directory.

Archive contents:
   Files:
       * build-release.py - Builds template and class archive for students.

   Directories:
       * dtx/ - contains ncsuthesis.dtx documented class file
           - The documentation can be built using "make" here.
           - See ncsuthesis.pdf for more information on the design.
       * template/  - LaTeX example files
       * other-sty/ - less common packages that may not be included
                              in a standard LaTeX distribution


The latest version of this package can be downloaded from github.com:
   https://github.com/jhykes/ncsuthesis

A recent version of the student template and class file is available at:
   http://www4.ncsu.edu/~jmhykes/latex.html

The NCSU ETD template website is:
   http://www.ncsu.edu/grad/etd/templates.html

Send thesis class bug reports or patches to Josh Hykes at jmhykes@ncsu.edu
