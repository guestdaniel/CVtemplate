Summary
=======
This repo contains a number of files to help users create a CV using LaTeX. It features an example CV which uses biblatex-apa to support APA-style citations as well as custom commands to automatically bold the user's name in those citations.

The .tex file
=============
The beginning of the preamble specifies paper and font size, font style, biblatex settings, and the location of the bibliography resource you want to use. The settings here are for biblatex-apa.  

The next section explains how to setup automatic bolding of your name. This is designed specifically for biblatex-apa, and will need adjustment for other citation styles. The key of the idea is to find the hex corresponding to your name in the ``.bbl`` file and put it in the right location in the preamble. 

Finally, the last portion of the preamble sets up the environments used to typeset the CV. First, ``step`` and ``twostep`` are defined, which are lengths corresponding to one indent and two indents relative to the left margin. ``aligngroup`` aligns two pieces of text, one flush left and another flush right. ``aligngroupin`` does the same, but with the left piece of text aligned one ``step`` from flush left. The ``indentsection`` environment is used to indent all sub-heading text one ``step`` from the left margin. The ``hangingpar`` environment is used to implement a hanging indent in the bibliography and lists. 

The rest should be fairly self-explanatory!

With questions, please contact Daniel Guest at guest121@umn.edu.
