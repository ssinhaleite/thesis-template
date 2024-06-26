LaTeX Thesis Template v.2.1.0

Institute of Neuroinformatics, UZH and ETH Zurich

If you are part of the NCS group, you need to add biblio from code.ini.uzh.ch as a submodule. Please check https://code.ini.uzh.ch/ncs/papers/biblio for more info.
If you are not, this template has an example of biblio and acronym file you need to populate.


You need to fill your information in the Titelblatt.doc and generate a pdf from it.
This page is mandatory for Doctoral Thesis at ETH and UZH.
(For double degree and UZH the page is available as a doc to be updated and generate a PDF. For ETH only the non-editable PDF is available, you will have to generate your own version of the PDF following the information listed.)


Adapted from 
> Copyright (C) 2004-2011
> Institute for Dynamic Systems and Control, ETH Zurich
> Original contribution by Eric Mueller (IMRT), 2004/04/02 
> Maintained by Soren Ebbesen (IDSC), sebbesen@idsc.mavt.ethz.ch

Original adaptation by Mohammad Ali, ali@ini.uzh.ch
Updates by Vanessa Leite, vanessa@ini.uzh.ch and Alpha Renner, alpha@ini.uzh.ch

=========================================
Change log:
=========================================

-----------------------------------------
Version 2.1.0: 2024/04/24, Vanessa Leite
-----------------------------------------

* Modify first page of the thesis: has to be the official page
* Add official page for double degree ETH+UZH doctoral thesis
* Add official page for ETH doctoral thesis (there's no editable version, just a template)
* Add instructions for abstracts in case of ETH doctoral thesis
* Add example of biblio and acronym file in case biblioncs is not accessible
* Add example of epigraphs

-----------------------------------------
Version 2.0.1: 2022/10/19, Alpha Renner, Vanessa Leite
-----------------------------------------

* Change doctype to scrbook
* add hypersetup
* Remove old bf commands
* Change Swiss Federal Institute of Technology to ETH Zurich
* Use full ini man instead of just head
* Print only used items in the acronym list 


-----------------------------------------
Version 1.5.1: 2022/06/30, Mohammad Ali & Vanessa Leite
-----------------------------------------

* Adaptations to include INI logo
* Use of biblioncs as subproject
* Add mandatory MNF page

-----------------------------------------
Version 1.4.1: 2014/13/03, Soren Ebbesen.
-----------------------------------------

* Minor bug-fixes

-----------------------------------------
Version 1.4.0: 2011/23/03, Soren Ebbesen.
-----------------------------------------

Major changes:

* Re-written in English

* Usepackages moved to ethidsc.sty

* Enables options st, bt, and mt

* Included mcode.sty for .m code formatting in documents


-----------------------------------------
Version 1.2.2: 2009/25/06, Soren Ebbesen.
-----------------------------------------

Major changes:

* none

Minor changes:

* Swapped page number and page title when using fancy header such that the page number is placed on the left of left-pages (even pages) and on the right side on right-pages (odd pages).

* Some additional efforts in the transition to a purely English template.

-----------------------------------------
Version 1.2.1: 2009/10/06, Soren Ebbesen.
-----------------------------------------

Major changes:

* none

Minor changes:

* Added sections on how to work with units and including code. Modified section on how to include graphics.

-----------------------------------------
Version 1.2.0: 2009/29/05, Soren Ebbesen.
-----------------------------------------

Major changes:

* Removed option ("dt" or "st") in  \usepackage[options]{ethidsc}. Instead the command \type{ARG} was created which is invoked by \maketitle. ARG is any string and intended to describe the type of report. Example \type{Master Thesis}. This is equivalent to \usepackage[dt]{ethidsc} in older versions. The motivation for this change was to remove the restriction

* Replaced file 'bibliography.tex' with 'bibliography.bib'. The .bib file is most conveniently created by a dedicated program for organizing references (such as Jabref (free), Bibdesk (free), or Endnote).  

* Replaced IMRT logo with IDSC logo.

* Translated last page to english. (German translation is still available using the \usepackage[german]{ethidsc}).

* Updated the text "statment regarding plagiarism" (last page) to reflect the official statement as of "Decreed in November 2008 by the Rector, ETH Zurich". This text is now See [http://www.ethz.ch/students/semester/plagiarism_s_en.pdf]

Minor changes:

* Renamed style-file ethimrt.sty to ethidsc.sty

* Renamed file Bericht.tex to Report.tex

* Replaced "H.P.Geering" with "R.D'Andrea"

* Included the hyperref package to enable hyperlinks within the PDF.

* Change name of template from "LaTeX -Template für Semester- und Diplomarbeiten" to "LaTeX Thesis Template v.1.2".

To do:

* Write and include introduction to organizing references using dedicated tools such as Jabref.
