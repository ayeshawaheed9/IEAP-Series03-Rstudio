# IEAP-Series03-Rstudio

Data Wrangling and ANOVA

The objective of this project is to reproduce the main result of a scientific article (Fig 3): the effect of task difficulty (ID) on movement time (MT) in three groups (ap, cp, pp). We clean the data, run a mixed ANOVA, fit a linear regression for each group, and build a figure for publication.

## Group Members & Contributions

Each part of the assignment was developed on its own Git branch. After review through a Pull Request, the work was merged into the main branch, which contains the final version of the project.

| Branch | Member | Contribution |
|---|---|---|
| Data_loading_and_cleaning | Ayesha Waheed | Creation of the public repository; sections 1.1–1.3 – Questions, data loading, count of missing data and data cleaning; review and merge of all the Pull Requests |
| Anova_and_data | Jeanne Le Roux | Sections 1.3–1.7 – Mean per participant, mixed ANOVA, regression by group, figure, PDF export and discussion |
| readme, sources, git-workflow, challenges, checklist, final-report | Jeanne Le Roux | README, data sources and references, Git workflow analysis, challenges and lessons learned, checklist, and final report (master document, link to the repository, final PDF) |
| main | Group | Final integrated version containing the completed work |

## Project Objectives

- Load and reorganize the data with the tidyverse.
- Find and remove the missing data (ID3 and R3).
- Run a mixed ANOVA (GROUP between, ID within) with the `ez` library.
- Compute the linear regression of movement time on ID for each group.
- Build a ggplot figure with the regression lines and equations.
- Export the figure as an 8 x 6 inch PDF.
- Compare our results with the article.
- Work collaboratively using Git and GitHub.

## Project Structure

```
IEAP-Series03-Rstudio/
│
├── data/
│   └── Results.txt
├── figures/
│   └── fig3_MT_ID.pdf
├── IEAP-Series03-Rstudio.qmd   (master document)
├── 02-anova_and_data.qmd       (included in the master document)
├── 03-git-workflow.qmd
├── 04-challenges.qmd
├── 05-sources.qmd
├── 06-checklist.qmd
├── IEAP-Series03-Rstudio.pdf
├── README.md
└── LICENSE
```

## Git and GitHub Workflow

Each part was developed on its own branch. We made regular commits with descriptive messages, pushed the branches to GitHub, and used Pull Requests to review the work before merging it into the main branch.

This workflow allowed us to:

- Work separately on different parts of the assignment.
- Keep track of each contribution.
- Review and improve the work through Pull Requests.
- Avoid overwriting each other's work.

## What We Learned

- Reorganize and check data with the tidyverse.
- Run a mixed ANOVA with `ezANOVA` and read its results.
- Fit a linear regression for each group.
- Build and export a figure with ggplot2.
- Use a master Quarto document that includes sub-documents.
- Use Git branches, commits and Pull Requests.
- Write clear commit messages, with only the message and not the Git commands.

## How to Use This Repository

Clone the repository to your computer:

```
git clone https://github.com/ayeshawaheed9/IEAP-Series03-Rstudio.git
```
