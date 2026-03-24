# Git & GitHub for Scientists — NIEHS Training Notebooks

Hands-on R Markdown notebooks for a 3-hour Git & GitHub workshop
designed for scientists at the National Institute of Environmental
Health Sciences (NIEHS).

## Platform

This training runs on **[Posit Cloud](https://posit.cloud)** (formerly
RStudio Cloud). No local software installation required.

## Workshop Structure (3 Hours)

| File | Module | Time |
|------|--------|------|
| `00_welcome_and_setup.Rmd` | Welcome, prerequisites, environment check | 10 min |
| `01_why_version_control.Rmd` | The problem, the solution, FAIR principles | 20 min |
| `02_setup.Rmd` | GitHub account, PAT, Posit Cloud project, Git identity | 25 min |
| `03_core_git_workflow.Rmd` | Stage, commit, push, diff, log, undo, stash | 40 min |
| — | **Break** | 10 min |
| `04_branching.Rmd` | Branches, PRs, merge conflicts, branch cleanup | 30 min |
| `05_github_for_teams.Rmd` | Issues, READMEs, releases, Zenodo, Pages, licensing | 25 min |
| `06_best_practices.Rmd` | .gitignore, security, commit frequency, renv | 15 min |
| `07_capstone.Rmd` | Full workflow: branch → commit → PR → issue → merge | 15 min |
| `quick_reference.Rmd` | One-page command cheat sheet | — |

## Getting Started

### Option A: From GitHub (recommended)

1. Log in to Posit Cloud
2. Click **New Project → New Project from Git Repository**
3. Paste this repository's HTTPS URL
4. Open `00_welcome_and_setup.Rmd` and knit it

### Option B: Upload manually

1. Log in to Posit Cloud and create a new project
2. Upload all `.Rmd` files to the project
3. Open `00_welcome_and_setup.Rmd` and knit it

## How to Use

- **Knit each notebook** to see the formatted reference material
- **Run exercises in the Terminal tab** (not the Console) for Git commands
- **Follow the slide deck** for visual explanations and live demos
- **Keep `quick_reference.Rmd` open** as a command cheat sheet

## Prerequisites

- A free GitHub account ([github.com](https://github.com))
- A free Posit Cloud account ([posit.cloud](https://posit.cloud))
- A modern web browser (Chrome, Firefox, or Edge)
- No prior Git experience required (basic R familiarity helpful)

## Key Learning Outcomes

By the end of this workshop, participants will be able to:

1. Configure Git and authenticate with GitHub using a PAT
2. Use the edit → stage → commit → push workflow
3. Read diffs and write informative commit messages
4. Create branches and open pull requests for code review
5. Use GitHub Issues to track tasks and close them from commits
6. Set up .gitignore to exclude sensitive and large files
7. Create releases and DOIs for citable code
8. Organize a scientific repository with standard structure

## Companion Slide Deck

These notebooks are designed to accompany the presentation
`git_github_training_niehs_v2.pptx` (72 slides).

## License

These training materials are provided for educational use at NIEHS.
