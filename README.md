# assignment-b4-hotz1

## What is this repository?

This repository contains files which I created for the fourth and final assignment ("Assignment B-4") of STAT 545B at the University of British Columbia. 

For this project, I created solutions to two exercises which were provided by the teaching team. The first exercise was to analyze a dataset of text from some source (I chose *A Christmas Carol* by Charles Dickens) and create a plot of the most common words which are in the text. The second exercise was to create a language similar to Pig Latin and write an R function which utilizes Roxygen2 tags to implement this translation.

## What are the files and folders in this repository?

The main folder in this repository only contains one file (`README.md`), which you are reading right now. In addition to this README file, the repository also contains two sub-folders, which are named `Christmas-Carol` and `Sheep-Flemish`. 

Here is some more detailed information about each of the files in this repository:
- [`README.md`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/blob/main/README.md): This is the README file which you are reading at the moment. This file is a standard README file for a GitHub repository, which is useful for orienting yourself with the files in the repository.


- [`Christmas-Carol/Exercise-1.Rmd`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/blob/main/Christmas-Carol/Exercise-1.Rmd): This RMarkdown file contains the code for the first of the two exercises (analyzing a text dataset) which were completed as part of this assignment. This file is split into a series of individual chunks which can be run one at a time in sequential order in an interactive R environment.
- [`Christmas-Carol/Exercise-1.md`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/blob/main/Christmas-Carol/Exercise-1.md): This is a GitHub-compatible markdown file which was created by knitting `Christmas-Carol/Exercise-1.Rmd` to 'GitHub-flavoured' markdown. The contents of this file are nearly identical to `Christmas-Carol/Exercise-1.Rmd`, but this file allows a reader to view all of the code in the Rmd file without requiring them to download any files.
- [`Christmas-Carol/Exercise-1_files/figure-gfm/`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/tree/main/Christmas-Carol/Exercise-1_files/figure-gfm): A folder within the `Christmas-Carol` sub-folden which contains 2 PNG files. These two files are the two bar plots created in the final chunk of `Christmas-Carol/Exercise-1.Rmd`, and these are the images which are displayed in the `Christmas-Carol/Exercise-1.md` document.
- [`Sheep-Flemish/Exercise-2.Rmd`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/blob/main/Sheep-Flemish/Exercise-2.Rmd): This RMarkdown file contains the code for the second exercise (creating a new language) which was completed for this assignment. This file is split into a series of individual chunks which can be run one at a time in sequential order in an interactive R environment.
- [`Sheep-Flemish/Exercise-2.md`](https://github.com/stat545ubc-2023/assignment-b4-hotz1/blob/main/Sheep-Flemish/Exercise-2.md): This is a GitHub-compatible markdown file which was created by knitting `Sheep-Flemish/Exercise-2.Rmd` to 'GitHub-flavoured' markdown. The contents of this file are nearly identical to `Sheep-Flemish/Exercise-2.Rmd`, but this file allows a reader to view all of the code in the Rmd file without requiring them to download any files.

## How do I use this repository?

Great question! 

If you would like to simply read the existing code and look at the work which I have put into each of these exercises for this assignment, then you can simply navigate to the two 'Github-flavoured' markdown files (`Christmas-Carol/Exercise-1.md` and `Sheep-Flemish/Exercise-2.md`) which can be accessed and read directly on your browser without any downloads.

However, if you would like to edit any of the code in the two RMarkdown files, or if you would like to play around with the code in those files in an interactive R environment, then it is best to clone the entire Git repository into a new folder on your machine, and then you can play with the existing code in the repoitory to your heart's content.

**Note::** Although the RMarkdown files (and their corresponding markdown files) are named `Exercise-1` and `Exercise-2`, these files are not directly related to one another, so you do not need to run (or even look at) the files in the `Christmas-Carol` sub-folder before the files in the `Sheep-Flemish` folder.
