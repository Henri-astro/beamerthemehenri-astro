# henri-astro beamer template

# Usage

To use the template the following files need to be at a place pdflatex can find:

 * beamercolorthemehenri-astro.sty
 * beamerinnerthemehenri-astro.sty
 * beamerouterthemehenri-astro.sty
 * beamerthemehenri-astro.sty
 * bgtitlepage.jpg
 
This can either be the local project directory or one of the global directories pdflatex uses. For Linux I recommend: ~/texmf/tex/latex/beamerthemehenri-astro
As an example for this package example.tex is procided.

# features

## background inmage

This template contains a background image for the title slide named "bgtitlepage.jpg". It shows the stellar cluster NGC 1850 and was made by Hubble and then processed by Gladys Kober (NASA/Catholic University of America). The background image can be overridden anytime by adding an own file named "bgtitlepage.jpg" to the project folder.

## colours

The colours are defined in the file beamercolorthemehenri-astro.sty. The three main colours used are defined at the top as rgb. All other colours are derived as mixtures of the colours. The colourtheme can, therefore, easily be changed based on the users wishes.
