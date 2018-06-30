# CDUX Development Notes

The Latex report for an experimental eLearning project for Charles Darwin University. The project was contracted by the School of Engineering an consisted of the installation and configuration of the Open Edx source code for use in the school. Additionally, an example course was created for a Project Management unit was created to demostrate the platform's capabilities for delivering learning experiences.

## Compiling Latex Files
The repository consists of the `.tex` files as well as any figures that were used in the report. To compile the `.tex` file from a Unix command line, first you will need to ensure that you have `texlive`, which can be installed using the command:
```
apt-get install texlive
```
To compile the `.tex` file, simply run the following from the terminal:
```
pdflatex test.tex
```