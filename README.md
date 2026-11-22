# Stat 184 HW #4.4 repo

This repo holds my reproducible data analysis report from HW #4.3 written in Quarto and rendered to PDF. It is allowing me to experiment with managing a repo and files.

## Overview

The report brings together work from across the course into one document
that anyone can render from the files in this repo. It has five parts in the QMD:
summary tables of diamond length, width, and depth, a plot of win
percentage against three-point attempts in NCAA women's basketball, a Monte Carlo estimate of the area
under the curve, a comparison of a plan-based GenAI prompt
with a generic prompt for tidying and plotting calcium data, and a reflection
on what I have learned in the course.

## Data Sources and Acknowledgements

- diamonds: built into the {ggplot2} package 
- team_box.csv: ESPN women's college basketball team box scores from the
  {wehoop} package
- calcium.csv: ulnar calcium measurements for 31 women over four years,
  provided with the Stat 184 assignment
- images/genericMeans.png and images/genericLines.png: generic GenAI
  prompt results provided by the instructor

## Current Plan

The report is complete and matches the PDF I submitted for HW #4.3. Any future
changes will be made on the dev branch and merged into main through a PR.
See `PLAN.md` for my full plans for the report and for this repo.

## Repo Structure

- `HW4.3_Reproducible_Data_Analysis.qmd`: the Quarto source for the report
- `HW4.3_Reproducible_Data_Analysis.pdf`: the rendered report I submitted
- `team_box.csv` and `calcium.csv`: data files the QMD reads in
- `images/`: the two PNG files the QMD displays
- `PLAN.md`: goals and steps for the report and the repo


## Authors

Joe Everett, Penn State University. Questions can be sent to jbe5346@psu.edu.