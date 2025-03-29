# Code Reviewing Template
A template for reviewing code that is part of a mathematical paper designed by Jeroen Hanselman as part of MaRDI (Mathematical Research Data Initiative) https://www.mardi4nfdi.de/about/mission

The template used for this technical review was adapted from the template made by Timmy Chan on https://github.com/TimmyChan 

## Installation Instructions
The template depends on the packages parallel.sty and FiraSans.sty. These will generally be installed automatically when using Overleaf or any kind of LaTeX package manager. Otherwise they might need to be installed by hand.

## Usage Instructions

To use the template one should edit all the section in the file code-review.tex. There are twelve sections. Each of them start with a header of the form containing some instructions on this particular section:

```
%====================
%====================
% FOR REVIEWERS TO FILL OUT (PART 1 of 12)

% Here you can write down the title of the paper and the names of the authors.
%====================
%====================
```

For many parts of the review it is possible to use the blue + or the orange - to indicate whether you found it a positive aspect or a negative aspect. You do not need to use them, but they give they allow authors to quickly see what was good and what could be improved. The corresponding commands are
`\mplus` and `\mminus`. 

## Performing software reviews
Tips on how to perform a software review one can be found in Sections 4 and 5 of 
https://arxiv.org/abs/2503.01541

The current template gives a general guideline. Depending on the needs of the software to be reviewed, it may be necessary to add or remove sections as needed. 
