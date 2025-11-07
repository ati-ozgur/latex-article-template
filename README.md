# latex article templates

This repository has latex templates for major publishers.
It tries to make it easy to change between publisher when submitting to journals.



## Journal templates

Every template starts with main as its name see below for templates.

- main.tex
- main-elsevier.tex
- main-IIEETransactions.tex
- main-sage.tex
- main-springer-nature.tex
- main-springer-svjour3.tex


Using latex input mechanism, template tries to be modular but some repetition still exists.
Templates use different mechanisms for author and addresses.
See below files.
You may have to add same information to different files due to this issue.


- authors.tex
- authors-elsevier.tex
- authors-IEEE.tex
- authors-sage.tex
- authors-springer.tex
- front-matter.tex
- front-matter-elsevier.tex
- front-matter-springer-svjour3.tex



## Github actions

Article templates have corresponding github action workflow so that you could see the pdf output.
Go to actions tab, and see the output files from workflows to see their outputs.

When you fork the repository, this will allow you to compile the latex in the github.

