# Welcome

Welcome to your Posit Academy project! This folder contains materials for analyzing COVID-19 data from the COVID Tracking Project using R.

## Project Structure

- **Quarto Documents (.qmd files)**: These are the milestone files where you'll complete your work:
  - Files are numbered 01-05 in sequence, building skills progressively
  - Each milestone introduces new Python data science techniques
  - You will complete milestone recreations and extensions within these files to advance through the project

- **data/**: Contains the COVID-19 datasets you'll analyze
  - Main files: `covid.csv`, `covid_state_pop.csv`
  - Milestone "solution" datasets for you to compare against your work

- **assets/**: Contains data dictionaries explaining the variables in each dataset

- **images/**: Contains milestone "solution" images for you to compare against your work

## Getting Started

**Step 1**: Install R packages you will need for this project:

1. Open your Console tab at the bottom of the IDE.
2. Run `renv::restore()` in your Console (this may take several minutes to complete).
3. Re-start your R session by clicking the Restart Console button (circular arrow icon) near the top-right corner of the Console.

Note: `renv::restore()` uses renv, a popular tool for managing reproducible R environments, to install all of the R packages included in the `renv.lock` file You will see output in the Console indicating that R packages are being installed. Wait for this to complete before proceeding.

**Step 2**: Open your first milestone file.

1. In the Explorer tab on the left, open the file `covid_01_quarto_visualize.qmd`
2. Follow the instructions in this file to complete the exercises
