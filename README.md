# COMP3104_Group2_Assignment

## Group Members
- Sanyoung Yoon (101503234) - [GitHub](https://github.com/sanYsan0)

## Project Description
This project is an assignment to practice version control, branch management, and continuous integration using Git and GitHub.

## Branching Strategy
Each member works on their own branch. All changes are merged into the main branch through pull requests.
Branches follow the naming format STUDENTID-Name, such as 101503234-Sanyoung.

## CI/CD Pipeline
This project uses GitHub Actions for continuous integration. The workflow runs automatically when changes are pushed or pull requests are opened.
The workflow file is located at `.github/workflows/ci.yml`.
It runs on `ubuntu-latest` and prints messages to confirm that the workflow is running.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/sanYsan0/COMP3104_Group2_Assignment.git
   ```
2. Enter the repository:
   ```bash
   cd COMP3104_Group2_Assignment
   ```
3. Create your own branch:
   ```bash
   git checkout -b STUDENTID-Name
   ```
4. No additional dependencies are required for this documentation project.
