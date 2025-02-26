## UNRELEASED

- renamed chapter 1 and 2 / tobi
- add full text of license for easier distribution / marcin-serwin
- switch to biblatex for bibliography generation / marcin-serwin
- replace bunch of links with citations / marcin-serwin
- use booktabs for table typesetting / marcin-serwin
- replace most of direct text formatting with logical markup in math chapter /
  marcin-serwin
- add biblatex tutorial / marcin-serwin
- use the new syntax for defining commands and environments in customizig LaTeX
  chapter / marcin-serwin
- add siunitx tutorial / marcin-serwin
- change document font back to Latin Modern / marcin-serwin
- update polyglossia tutorial / marcin-serwin
- rewrite tables intro / marcin-serwin
- rewrite fancyhdr intro / marcin-serwin
- lint files using chktex and latexindent / marcin-serwin
- add listings and minted tutorial / marcin-serwin
- add logical markup introduction / marcin-serwin
- update TeX and LaTeX history / marcin-serwin
- restructure the first two chapters / marcin-serwin
- switch to `LuaLaTeX` / marcin-serwin
- use `minted` throughout the booklet / marcin-serwin
- add 'deprecated' appendix / marcin-serwin
- standardized font size and `textwidth` in all three versions of the booklet /
  marcin-serwin
- removed outdent and adjusted examples / marcin-serwin
- switch to `autoref` from `hyperref` / marcin-serwin
- use `microtype` / marcin-serwin
- update license / marcin-serwin
- drop the `2e` from the title / marcin-serwin
- redesign the title page with illustration / marcin-serwin
- restructure the repo / marcin-serwin
- update readme / marcin-serwin
- drop the lssymb appendix / marcin-serwin
- rewrite the math appendix to focus on `unicode-math` / marcin-serwin
- add sections about changing math fonts / marcin-serwin
- rewrite the beamer section / marcin-serwin
- rewrite the graphics chapter to focus on TikZ / marcin-serwin
- reviewed graphics chapter @rmrstar

## 6.4 2021.03.09

- a bunch of spelling issues fixed

## 6.2 2018.02.28

- drop the babel apppendix
- switch to using polyglossia for lshort itself
- rearranged the multilanguage section again

## 6.1 2018.02.27

- rearranged the multilanguage section
- moved the graphicx section into the 2nd chapter

## 6.0 2018.02.26

- removed most mentions of dvi
- moved bable into the appendix and point people to polyglossia
- have people use xelatex
- assume pdf everywhere ...
- update inputenc fontenc info
- dropped portugese section since it does not contain any special information
  apart from the things already mentioned in international language support

## 5.0.6 2015.06.13

- fix super vs subscript in math chapter
- added note on github
- improvement to the align text

## 5.0.5 2015.07.18

- new text for korean support
- better spaceing trick for multiline equations

## 5.0.4 2014.10.29

- a ton of language fixes by Martin Jenkins
- add reference to structure section when introducing 'usepackage'

## 5.03 2014.4.25

- fixed fixes in appendix

## 5.02 2014.4.21

- better example for spaceing
- fix spelling of Photoshop and AUCTeX
- correctly spell greek technology
- fix CTAN links
- mention booktabs package
- minor typos
- improved logic in appendix on installation

## 5.01 2011.4.6

- many minor wording fixes by Robert Funnell
- massive language surgery on the math and pdf sections by Robert Funnell
- simplified pdf font section
- use {\\greektext teknolog'ia}
- better explain the empty parameter for stopping space gobbling
- Added missing source files
- added section on / - Nikos Pothitos

## 5.00 2010.12.14

-a XeLaTeX documentation added by Axel Kielhorn

- misc language fixes suggested by Robert Funnell
- misc language fixes suggested by Jordi Serra i Solanich

## 4.31 2010.06.24

- fixes for new pgf examples
- add note on sumatra pdf

## 4.30 2010.06.18

- Updated installation appendig. Remove Texmate since it is not OSS software and
  add Texshop and Texmaker instead.
- use microtype for optimized character positioning
- updated graphics chapter with more emphasis on PGF/TikZ integrated several
  examples by Andras Salamon
- add note about the layouts package to the layout page
- spaceing after e.g. fixed as suggested by Mike Lee
- it is --update-fndb not -update-fndb (Rockrush Engch)
- integrated suggestions from the Manuel Pégourié-Gonnard and Samuel Colin
  - make CTAN links more uniform throughout the document
  - do not type ASCII in tt
  - be less opinionated on \[ vs equation
  - add note on how to deal with accented characters and makeindex sorting
    limitations.
  - update notes on how todo documents that work in both latex and pdflatex
  - replace acrobat reader by pdf reader and acrobat distiller by pdf convertor
  - use francais instead of frenchb and mention numprint.
  - note about linux distros splitting tex distors up into many packages
  - do not mention java in math-graphics
  - eqref does work with tag
  - equation is from latex, equation- is from amslatex ... (footnote fix)
  - textcolor works fine with hyperref by now

## 4.27 2009.11.16

- add a second argument to the example of the new command
- better explanation of the textcomp degree symbol commands
- Now that barack is in office we do not need all these 'you can's in the text
  anymore removed about 1k of them.
- fix documentation on hyperref default settings by Gust Eilinger
- better english for the apppendix by Tobias Vidarssønn Langhoff.
- use \\textbackslash instead of $\\backslash$.
- added notes on mongolian support by Dorjgotov Batumongke
- added big update to math from stefan m. moser
- added letter size to the build system

## 4.26 2008.09.25

- fix some spellig in the PGF section

## 4.25 2008.09.25

- added a section in TikZ&PGF graphics
- remove xy pics instead
- added an appendix on installing latex
- Added arraystretch and colsep to table section
- Removed references to Corel Draw
- Don't talk about 'macro package' when introducing latex no one knows what this
  is anyway.
- Fix for sample correlation formula on page 74 by Josue Guzman

## 4.24 2008.02.08

- A ton of fixes for the updated math chapter by Barbara Beeton herself.

## 4.23

Math Chapter reworked by Lan Thuy Pham:

- The amsmath package is now introduced in the beginning of the chapter, and it
  is assumed that the reader has loaded the package.
- Wrote a short intro to AMS-LaTeX.
- Added a bit about: partial, (wide)hat, bar, pieceswise functions, and from
  amsmath: dfrac, tfrac, tag, different matrix environments.
- Modified examples: equation, equation-, \\text, Greek letters, exponents ans
  subscripts, (c/l)dot(s), under/overline, under/overbrace, \\vec, \\frac,
  \\binom, stackrel, delimiters, align/eqnarray, long equations, array, matrix,
  spacing, phantoms, (bold) math fonts, \\displaystyle...
- Removed: ( ) and the "math" environment, displaymath, subarray, eqnarray, some
  of the array and phantom examples, textrm.
- Added Note about upper case Greek letters.
- Added a new table: Arrows as Accents.
- Rearranged the "Delimiters"-table a bit.
- Added \\clearpage after the non-amsmath stuff (to stop LaTeX from
  complaining).
- Added a couple of labels.
- Added a reference to Math Fonts (\\ref{mathfonts}) at Math Alphabets.
- Rearranged some of the ams-tables to optimise the space.

## 4.22 2007.06.30

- fixed my email address

## 4.21 2007.06.26

- removed eurofont from the archive since the license does not allow us to
  redistribut them ...
- added \\mathring to list of math accents
- make a note that label must come after the caption.
- changed wording in the descriprion of the stretch command by tobi
- replace metafont and metapost with their logos by tobi
- improved wording for pagebreak, linebreak commands by Robin Fairbairns
- fix the last page counter by Morten Høgholm

## 4.20 2006.05.31

- fixed spurious noindent on page iv

## 4.19 2006.05.30

- added missing files to source archive

## 4.18 2006.05.30

- section headings should be leftaligned
- added notes on amsthm suggested by Daniel Flipo
- improved explanation ifpdf package
- use \\textasciigrave for \` and \\textquotesingle for ' by Tahir Hassan
  <tah16@leicester.ac.uk>
- Reworde the mentioning of the preamble where I introduce the comment command.
- updated eurofonts again based on Daniel Flipo's work for the french lshort
- we should use utf8x for inputenc
- mention unicode option for hyperref
- mention active language after calling usepackage bable with multiple
  languages.
- Added section on writing greek text by Nikolaos Pothitos
  <n.pothitos@di.uoa.gr>

## 4.17 2005.09.27

- removed eurosans package I did never get it to actually display a symbol with
  all the other euro packages loaded at the same time.
- made mentions of Latin and Cyrillic consistently capitalized
- added note on Latin modern outline fonts to replace EC in pdfs
- added proc and minimal class
- mention companion 2nd edition
- update for ifpdf section from Morten Høgholm
- print from 4.1 to chapter 5 for pure latex graphics

## 4.16 2005.05.08

- include properly rendered PDF version with the distribution

## 4.15 2005.05.08

- replaced pdfscreen with beamer for presentations. Used text from the french
  lshort by Daniel Flipo as a basis for this.
- eqref requires amslatex
- use \\centering to put figure into the center as begin/end{center} adds extra
  vertical space as suggested in
  http://www.ctan.org/tex-archive/info/l2tabu/english/l2tabuen.pdf
- fixed missing , after pdfauthor on page 77
- added note on texdoc
- renames longtabular to longtable
- added notes on greek TeX -- Dimitrios 'sehh' Michelinakis
  <dimitrios@michelinakis.gr>
- added notes about pronunciation of ch in ach

## 4.14 2004.04.04

- improved explanation of raisebox parameters
- added pagelayout parameters to index
- added caption to includegraphics example
- better examples for math fonts -- Vadym Lepetyuk <lepetyuk@econ.umn.edu>
- note in pdf fonts section that fonts may work just fine in a modern tex
  installation
- have label inside caption
- rephrase the back-tick grave stuff
- it's textcomp and not texcomp

## 4.13

- added comment on bad rendering of example in Quotes section
- added section on abstract
- added note on textcelsius and texdegree in texcomp
- added section on ignorespaces and ignorespacesafterend

## 4.12

- fixed order of hebrwe letters to be 'alphabetic'
- fixed colons in table 3.7 (Rightarrow was captured by marovsym)
- added cyrguide bibliogrphay entry back in ...
- table head in eurotable translated to english
- remove kees.fig from Makefile
- some wording fixes to the cirillic section.
- added pdfstringdefDisableCommands to the preamble to fix some broken bookmarks
  -- Maksym Polyakov
- reworded the paragraph on the position argument of the newsavebox command.

## 4.11

- added graphic.tex file to source distro

## 4.10

- Integrated EuroSymbol table from the french translation by Daniel Flipo
- Created new chapter: graphics with description on the picture environment by
  Urs Oswald.
- Moved Xy pics to the graphics chapter
- compile with cm-super fonts for now
- updates to the hyperref syntax table -- Maksym Polyakov
- rewritten sectons on fontencoding, inputencoding -- Maksym Polyakov
- section on cyrillic support -- Maksym Polyakov
- turned CTAN references into URLs as suggested by Maksym Polyakov
- minor updates to pdfscreen section as suggested by Maksym Polyakov
- other little spellers
- get rid of color in ps output ... we do not need it ... tobi
- added note on p{} to tabular section
- minor fixes to pdf section --- Matthias Dreier
- added note on changeing baselineskip instead of using linespread.
- added example for using the index command.

## 4.0

- many minor fixes and edits in pagebreaks
- added note on cm-super
- punctuation, wording, big patch from Baron Schwartz
- Translated and integreated the pdfTeX description from the franch version of
  lshort.
- Added descrion of the .fd files
- \\part is available in article too
- small backports from the french translation
- drop atop and choose. Replace by binom
- put notes on Float Placing Permissions where they belong
- added eqref
- mention landscape option of default document classes
- mathcal update
- changed section headings in first sample
- drop latex structure figure from the intro as it is way to complex for a
  beginner to understand.
- drop LaTeX2e story ... who care these days
- added note on swiss use of \>\>guillemets\<\<
- added note on eurosymb
- added note on dvipdf
- added article on Korean Support
- added Xy Pic intro
- more symbols aded -- alex mai

## 3.21

From Tobi

- Added some notes on problems when running latex to section 1.5
- added oddsidemargin to layout graphics
- added note on the AE package
- added extension and font indexes
- mention optional label in bibitem
- rephrase hyphenation explanation
- added \\aa to index
- rearranged PageLayout section From Alexander Mai
  <mai@migdal.ikp.physik.tu-darmstadt.de>
- mini rewrites for math explanations
- improved makefile
- improved table environment spec

From Daniel Flipo <daniel.flipo@univ-lille1.fr>

- section on french language support

From Maksym Polyakov <polyama@myrealbox.com>

- parbox is not an evironment
- line 248 rephrasing

## 3.20

From Alexander Mai <st002279@hrzpub.tu-darmstadt.de>

- tabular presentation of input encodings
- description of a typical commandline latex session
- \\X{\\lvert}&\\X{\\rvert}&\\X{\\lVert}&\\X{\\rVert}
- bigskip smallskip description
- new ctan reference
- cdot for the math section

From Tobi

- added lshort.ist to insert letters between index sections
- added comment on plus and minus in setlength
- degree symbol
- moved fragile commands section to chapter 2
- no more bad boxes ... neither over nor underfull
- no more oscilating text

From Many

- spelling fixes

## 3.19

changed wording on \\apendix \\frontmatter \\backmatter ... fixed pagebreaks in
math chapter

## 3.18

compile fixed for environments where TEXINPUTS is set replace the environemnt
command with lscommand it seems command is too common .. (Alex Mai)

## 3.17

Added more info on the inputenc package. Added Section on German Language
support. Sections for other languages are welcome. Better explanation of the
\\section\[xxx\]{yyy} syntax Changed wording for Cross Ref Changed wording on
Quotation Marks added note on fbox. added \\underline command \\cleardoublepage
goes to a righthand page added \\cline added section on package installation
contributed by Joseph Hilferty

## 3.16

Fixed upload procedure Some spelling fixes Updated old URLs

## 3.15

Integrated a number of spelling and logic fixes by Björn Hvittfeldt

## 3.14

Even better Makefile Update TODO

## 3.13

Better Makefile Added description of Today, TeX, LaTeX, LaTeXe Added description
of file extensions you will find when working with latex Some CTAN references
fixed Better explanation for hyphenation command Added paragraph on typesetting
tildes ... Added example with multicol and borders (|c|) Added Hamster
disadvantage ... How todo a tilde

## 3.12

Replaced first section (TeX) as suggested by Michael John Downes in order to be
more in sync with the real events ...

## 3.11

better explanation for sloppy/fussy \\sin and frinds in index pointer to
whitespace after non argument commands information in custom.tex

## 3.10

removed some exess files from tar files

## 3.9

- included a number of minor fixes from Alexander Mai ...

## 3.8

- Added sections on \\phantom and \\protect commands, based on a contribution
  from Alexander Mai
- Added section on lines in array environments ... thanks Alex
- rephrased newcommand section ... again thnaks to Alex

## 3.7

- re-release to for some even spelling :-)

## 3.6

- released on CTAN ...

## 3.5

- even smaller factual errors corrected ...

## 3.4

- minor spelling fixes

## 3.3

- lots of small patches from Prof Ripley ...
- fixed compile problem on first run ...
- properly packaged the whole thing ....

## 3.2

- added better explanation of the difference between newline and linebreak
- added about 1000 spell and detail fixed contributed by Hanspeter Schmid
- added new section: The Structure of Text and Language contributed by Hanspeter
  Schmid
- added more verbose explanation about babel and hyphenation

## 3.1

- Var spell and other fixes. Especially the ftp.shsu.edu reference has been
  fixed.

## 3.0

- Restructuring of the Chapter 4 for didactical reasons ...
- moved some bits to the new Chapter 5.
- added 15 pages of new material ...

## 2.3

- it's slides and not slide ... p8
- pointer to foiltex added ... p8

## 2.2 non beta 13/10/97

- made the thing compile with pdftex and hyperref

David Frey:

- Sensible copyright notice
- some mathematical error in math mode
- correct Murphy ...

Cyril Goutte:

- typos

Martin Maechler:

- an Inch is exactly 25.4 mm!

## 2.2 7/11/95

Christian Kern:

- Spelling, and some suggestions for new stuff to inlcude

Young U. Ryu:

- Spelling and some errors in latex

Cyril Goutte:

- Some additions for math

Brian Ripley:

- Spelling, LateX 95/12/1 compatibility
- Some more real english .... :-)
- AMS-LaTeX now prefers eucal to euscript, so he has altered both lssym.tex and
  lshort2e.sty.
- He has corrected some examples in chapter 3 which would be regarded as bad
  practice in mathematical typesetting.
- He has added a section on bold symbols, and conditionals for amsbsy.

## 2.1 17/6/1995

Rasmus Borup Hansen:

- tonns of spelling mistakes and some suggestions for more logic ...

Josef Tkadlec:

- some spellings
- all new hopefully even more usefull maths tables ...

## 2.0 5/6/1995

Mike Ressler:

- Fixed Loads of spelling Mistakes.

## 1.9.9: 16/5/95

Tobi:

- General Makeover
- Added Preface.
- Added example to math.tex
- Introduced intro environment. I am going to add a short describtion about what
  the user can expect, to each chapter.
- Page Layout. spec.tex now contains a copy of the Geometry page layout
  parameters page. Provided by the layout package from the tools bundle.
- newcommand, newenvironament and newtheorem are described.
- new dynamic document title
- using fancy headings for header.

## 1.2: 8/2/95

Tobi: Revoved all | | in an attempt to make the document latex2html compatible
... failed :-(

Elliot:

- Odd spelling mistakes

David Jones:

- "Whitespace Description" ...

Byron:

- Many Spelling fixes Some requests for examples

Partl:

- Fixed Irene Hyna addr

Martien:

- "Character" spelling

Claus:

- ref to indexing without backslash ...

## 1.1: 17/11/94

Eric:

- Spelling.
- Removed numerical from section 1.3.3 (suggesting \\3 as a valid command)
- \\quad as MATH spacing
- No Pagenumber on first Page

Mike:

- Fixed @{} Discussion (thanks)

David:

- Letter case in \\hyphenation ignored
- \`|-|.''
- shelf\\mbox{}ful because TeX can \`forget' {} after hyphenation attempt
- pointer to dcolumn package
- standard calsses assume \[tbp\] !
- Pointer to amstex and exscale package added to \\big description
- Thanks for symbols.tex
- |-| and | | as forbidden delimiters with verb
- refrence to amsfonts removed
- LaTeX \\vspace works within a paragraph ... (-\> normally)
- Pointer to graphguide.tex

Tobi:

- \`horizontal' and Page Style Indexentries
- Odd Spell Fix
- pagestyle index entries
- Commented out display style example, to keep total size down to 58 Pages
- Fixed eufrak problem thanks David and Martien
