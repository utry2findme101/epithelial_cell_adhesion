# Project Title

Compute pairwise correlation of proteins

## Description

The protein data is supplied as an input file (Excel), one column/gene. This Jupyter Notebook application computes pairwise correlation among these proteins and stores the results to an output file (Excel). First cell of the notebook houses the names of the data files.

The data pipeline includes data clean up, validation, and processing. Data were read into a Pandas DataFrame and missing values were replaced by NaN. Every pairwise comparison was validated to ensure that at least 5 values were non-null values, using the dropna method with a threshold of 2. 

Output file has various worksheets including the input dataset, cleansed and pairwise correlation, both in tabular form and long column format. Configuration cell parameter (see first cell of the notebook), SPECIFIC_PROTEINS, notes specific proteins, if any, for which pairwidse correlation are stored as separate worksheets - one for each protein in the SPECIFIC_PROTEINS list.
#       



## Getting Started

### Dependencies

The application was tested with Anaconda (version below) on Windows 11 version 25H2 (OS build 26200.8655). It can also be run on GoogleColab (see insuructions under "HOW TO" below).

* Name                    Version                   Build  Channel
* _anaconda_depends         2022.10                  py39_2
* anaconda                  custom                   py39_3
* anaconda-anon-usage       0.5.0            py39h8ddfbff_0
* anaconda-client           1.11.0           py39haa95532_0
* anaconda-navigator        2.6.3            py39haa95532_0
* anaconda-project          0.11.1           py39haa95532_0



### Installing

* GitHub repo: https://github.com/utry2findme101/epithelial_cell_adhesion
 
### Executing on a desktop with Anaconda

* Download the zip from GitHub:

	* Launch the GitHub repository.
	* Click the green Code button located on the right side above the file list.
	* Click Download ZIP from the dropdown menu.
	* Extract the downloaded .zip file on your computer to view the files.

* How to run the program

	* Launch AJupyter Notebook
	* Navigate to the unzipped folder
	* Navigate tot he subfolder "notebooks."
	* Pull down "Cell" and hit "Run All."

### Executing on Google Colab

* Go to url: https://colab.research.google.com/
* Under Open notebook, click "GitHub."
* in the next box enter the GitHub URL below and press enter:
    github.com/utry2findme101/epithelial_cell_adhesion
* Click 01_pairwise_correlation.ipynb
* At this point, the notebook opens up in Google Colab.
* Click "Run All" to run all cells in sequene

## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

## Authors

Ray Kresman kresman@bgsu.edu

Carol A. Heckman heckman@bgsu.edu

## Version History

* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)

* 0.1
    * Initial Release

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* [awesome-readme](https://github.com/matiassingers/awesome-readme)
