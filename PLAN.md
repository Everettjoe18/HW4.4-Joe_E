# Plan

**Goal:** Build one reproducible Quarto report that renders to PDF with no
code in the body.

- Sub Goal: Make three tables of diamond length, width, and depth by clarity.
- Sub Goal: Recreate my HW #3.4 BTAA plot with a caption, alt text, and
  narrative.
- Sub Goal: Recreate my Monte Carlo small multiple as sub figures.
- Sub Goal: Write a plan for the calcium data, use it as a GenAI prompt, and
  compare the result to the generic prompt.
- Sub Goal: Reflect on what I have learned in the course.

**Needs:** R, RStudio, Quarto, TinyTeX, the {tidyverse} and {knitr}
 packages, the diamonds data, team_box.csv, calcium.csv  my HW
#3.2 and #3.4 code and feedback, the Quarto Crash Course, and the generic
prompt screenshots.

**Steps:**

1. Set up the YAML header for PDF output with code hidden by default.
2. Load packages in a setup chunk.
3. Wrangle the diamonds data and make one table chunk per dimension.
4. Load and wrangle team_box.csv, then make the BTAA plot chunk.
5. Write the Monte Carlo functions and make the four-panel figure.
6. Write my calcium plan, prompt the GenAI tool with it, and add its code.
7. Add the generic prompt screenshots as figures.
8. Write narrative text for every table and figure with cross-references.
9. Write the reflection and the GenAI usage appendix.
10. Add the code appendix chunk and render to PDF.
11. Proofread the PDF and check every number against the output.


**Goal:** Store the HW #4.3 report in a public GitHub repository

- Sub Goal: Use a main branch and a dev branch for changes.
- Sub Goal: Track work with labeled issues that commits close.
- Sub Goal: Write good commit messages that are complete.
- Sub Goal: Merge dev into main with a pull request so main stays up to date.

**Needs:** A GitHub account, GitHub Desktop, the HW #4.3 QMD, PDF, data
files, and images, and a README.

**Steps:**

1. Create a public repository on GitHub with a README.
2. Create a dev branch from main.
3. Open labeled issues for each piece of work.
4. Clone the repository with GitHub Desktop and switch to dev.
5. Add the QMD, PDF, data files, and images in a commit that closes its issue.
6. Rename the report files to clear names in their own commit.
7. Add a coding style comment to the QMD.
8. Fill out the README and this plan.
9. Open a pull request from dev into main with a title and description.
10. Merge the pull request and confirm that every issue is closed.