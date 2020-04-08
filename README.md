# SASTRA Deemed University Project Report

Compiler user: XeLaTeX

## Files
* `projecttemplate.tex` - The file that generates the PDF
* `projectreportcommands.sty` - The package that provides commands for report
* `projectrreport.cls` - The definition of the document class
* `projectreportbib.bib` - The file that holds bibliography information

### The Document Class - `projectrreport`
This file defines how the document is structured. This includes Margins, Fonts, styles for Table of Contents, References, etc.

Using this as the document class makes sure your document looks right.

### The Commands
Most of the commands used here are defined in the file `projectreportcommands.sty`.

* `\defstudentnameone` - This command is used to set the student one's name. Other commands are: `\defstudentnametwo, \defstudentnamethree`
* `\defstudentregnoone` - This command is used to set the student one's reg no. Other commands are `\defstudentregnotwo, \defstudentregnothree`
* `\defstudenttitleone` - This command is used to set the title for the student (Mr./Ms.). Other commands are `defstudenttitletwo, defstudenttitlethree`.
* `\defstudyduration` - Sets the duration of study
* `\defprogramme` - The program you are enrolled in (Ex. Computer Science and Engineering)
* `\defguide` - Sets the name of the guide
* `\defguidedesignation` - Sets the designation of the guide
* `\defguideinstitution` - Sets the institution to which your guide belongs to
* `\defdegree` - Sets the degree (B.Tech Computer Science and Engineering)
* `\defsemester` - Sets the end of the current semester (May 2020)
* `\defschool` - Sets your school (School of Computing)
* `\defpronouniwe` - Sets your pronoun I/We
* `\defpronounmeus` - Sets your pronoun me/us
* `\title` - Sets the title of your work
* `\makereportfirstpage` - Generates the first page for your report
* `\bonafide` - Generates the bonafide certificate for your work
* `\acknowledgement` - Creates the acknowledgement page with the content you pass as argument.
* `\fakesection` - Creates an entry in the Table of contents

### Built in Commands of Latex
* `\tableofcontents` - Automatically generates the table of contents page
* `\bibliography` - Generates the References section
* `\listoffigures` - Generates a list of figures
* `\listoftables` - Generates a list of tables


For more info on LaTeX and more of its built in commands, click [here](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes).
