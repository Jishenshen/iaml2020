# IAML 2020 - INFR11182 (Level 11) Assignment 1
This is the repository for Assignment 1 for IAML 2020.

**N.B.: This is the assignment for the Level 11 version of the course. If you are on the Level 10 course (i.e. likely an undergraduate student), then you should use [this](https://github.com/uoe-iaml/INFR10069-2020-CW1) version instead.**

## Repository Contents

 * `IAML_2020_CW1_INFR11182_Instructions.pdf`: This is the pdf with the question-sheet for the assignment.
 * `Assignment_1.tex`: This is the template you should modify to writeup your assignment.
 * `style.tex`: This is the style file for the assignment template. **Do not modify** this file in any way.
 * `data`: This is a directory (folder) which contains all the data you need to complete the assignment.

## Conda Environment

For this assignment you **must** use the same versions of the packages that are specified in the [IAML Labs repository](https://github.com/uoe-iaml/iaml-labs). 
Failing to do will result in you loosing points. 

## Building the PDF

This repository provides a latex template (`Assignment_1.tex`) for generating the final PDF that you will submit. 
You **must not** edit the style or formating of this document.
The only thing you need to do is enter your student number (see PDF for instructions) and put your answers in the correct answer boxes. 

You have a few options to create the final PDF:
* From a DICE machine you can run `pdflatex Assignment_1.tex` twice from the command line to compile the PDF. 
* You can do the same from your own computer, provided you have latex and all the necessary packages installed. Unfortunately, we do not support troubleshooting this step for you. 
* You can also use a free browser based latex editor such as [Overleaf](https://www.overleaf.com). **If you use such a tool, make sure to keep your document private and do not share the link to it.** 


## Submitting the Final PDF

Instructions will be provided on the IAML Learn page telling you how to upload your final PDF to Gradescope. 


## FAQs
Updated 13th October 2020
* Piazza private questions to instructions should not be used to request hints
* If a particular hyperparameter or setting for an algorithm is not specified in the question, it is implied that you use the default sklearn settings
* Unless you are requested to implement something yourself you can use the provided sklearn or numpy functions
* For questions where we ask for code (e.g. Question 1d), we do not expect you to re-implement low level functions such as matrix multiplication yourself - use numpy
* For questions where you are asked to plot the the data and the specific split is not specified (e.g. Question 3b), you should plot the train data
* Do not split any of the data into train and validation unless requested to do so
* `faces_train.csv` mentioned in the question sheet refers to `faces_train_data.csv` in the Github repository. The same is also true for `faces_test.csv`
