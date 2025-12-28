# Instructor Setup Guide

## 1. Repository Setup
- This repository already contains the basic structure.
- Customize the `README.md` and `_config.yml` with your specific language and theme.
- Update the "Current Semester Theme" section in `README.md` and `index.md`.

## 2. Labels
Create the following labels in the repository (via GitHub UI):
- `status:proposed` (color: #FBCA04)
- `status:approved` (color: #0E8A16)
- `status:in-progress` (optional, color: #0052CC)
- `status:published` (optional, color: #5319E7)

These labels help track the progress of student proposals.

## 3. GitHub Pages
1. Go to **Settings** → **Pages**.
2. Under **Source**, select **GitHub Actions**.
3. The workflow `.github/workflows/pages.yml` will automatically deploy the site on each push to `main`.
4. The site will be available at `https://[username].github.io/living-culture-journal/` after the first successful deployment.

## 4. Student Onboarding
- Share the repository URL with students.
- Walk them through the CONTRIBUTING.md guide.
- Demonstrate creating an issue using the template (`.github/ISSUE_TEMPLATE/proposal.md`).
- Show how to create a branch, commit changes, and open a pull request.

## 5. Sample Content
A sample article is provided in `articles/sample-article.md`. You may keep it as a reference or delete it before the semester begins.

## 6. End-of-Semester Release
After all articles are merged, create a GitHub Release:
- Tag: `v1.0.0`
- Title: "Living Culture Journal - [Semester] [Year] Edition"
- Include release notes thanking contributors and summarizing the journal's contents.
- This creates a permanent, archived snapshot of the class's work.

## 7. Optional Enhancements
- Add a `docs/` folder for additional resources (style guides, writing tips, etc.).
- Customize the Jekyll theme by editing `_config.yml`.
- Set up branch protection rules for `main` to require pull request reviews.
