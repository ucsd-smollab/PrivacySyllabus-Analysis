# PrivacySyllabus-Analysis

This repository contains scripts to analyse the data collected from courses and syllabuses.

## Repository Structure

- Overall Analysis : This folder contains the following:
	- `Analysis.ipynb`: A script to perform basic analysis on the data.
	- `all-university-dataset.csv`: This csv file contains all the universities in our dataset
	- `UniversitiesWithNoPrivacyCourses.csv`: This csv file contains all the universities which were identified having no mention privacy in their courses in our dataset
	- `UniversitiesWithPrivacyCourses.csv`: This csv file contains all the universities which were identified having the mention of privacy in their courses in our dataset
	- `InstructorData.csv`: This csv file contains all the instructor data for courses which had privacy mentioned in them.
	- `SyllabusData.csv`: This csv file contains all the syllabus data received from instructors.
	- `Plots.xlsx`: This excel file contains the plot (DistributionOfUniversityCategories.png - stacked bar chart). The data present in the excel is obtained from the results of Analysis.ipynb