# Contributing to the Living Culture Journal

## Overview
This document outlines the collaborative workflow for contributing to the Living Culture digital journal. Please follow these steps to ensure a smooth and professional contribution process.

## Phase 1: Proposal and Planning (Using Issues)
1. **Explore the Repository:** Read this CONTRIBUTING.md and the README to understand the project's theme, goals, and guidelines.
2. **Propose Your Topic:** Each student (or group) must create a new **Issue** in the repository.
   - **Title:** Use a clear title for your proposed article/chapter (e.g., "Proposal: The Role of Tapas in Spanish Social Life").
   - **Body:** In the issue description, outline your topic, explain its cultural significance, and list the types of content you plan to create (e.g., 800-word article, 5 original photos with captions, a short embedded video, a glossary of 5 key vocabulary terms).
   - **Label:** The instructor will apply a `status:proposed` label to your issue. Once your topic is approved, the label will be changed to `status:approved`, and the issue will be assigned to you.

## Phase 2: Content Creation and Drafting (Using Branches)
1. **Create Your Branch:** Once your issue is approved, create a new **branch** from the `main` branch. Your branch should be named clearly based on your topic (e.g., `feature/tapas-in-spain`).
2. **Develop Your Content:** Work on this branch, creating your article as a Markdown file (e.g., `tapas-in-spain.md`) within the `articles/` folder. Create a sub-folder for your media assets (e.g., `images/tapas-in-spain/`).
3. **Commit Your Work:** As you write and add files, make regular **commits** with clear messages describing your progress (e.g., "Add draft of introduction and history section," "Upload photos and add captions").

## Phase 3: Review and Publication (Using Pull Requests)
1. **Submit a Pull Request (PR):** When your article and all media are complete and ready for the journal, open a **Pull Request** to merge your branch into the `main` branch.
   - **Title:** The PR title should be descriptive (e.g., "Add article: The Role of Tapas in Spanish Social Life").
   - **Body:** In the PR description, link to your original planning **Issue** (using the `#` notation, e.g., `Closes #23`). Provide a brief summary of your work and highlight any areas where you would particularly like feedback.
2. **Peer and Instructor Review:** The instructor and assigned classmates will review your PR.
   - They will leave **inline comments** directly on your Markdown file, suggesting grammatical corrections, asking clarifying questions, or offering praise for well-written phrases.
   - General feedback will be left in the main PR conversation.
3. **Revise and Finalize:** Respond to the feedback by making new commits to your branch. The PR will automatically update to show your changes.
4. **Merge:** Once the PR is approved and all feedback is addressed, the instructor will **merge** your branch into `main`. Your article is now officially published in the "Living Culture" journal!

## Phase 4: Curation and Archiving (Using Releases)
1. **Final Release:** At the end of the semester, after all articles have been merged, the instructor will create a **GitHub Release**.
   - **Tag Version:** This will be tagged as `v1.0.0`.
   - **Release Title:** "Living Culture Journal - Fall 2024 Edition" (or the appropriate semester).
   - **Release Notes:** The notes will thank all contributors by name and provide a summary of the journal's contents.
   This creates a permanent, archived snapshot of the class's work for that semester, which can be easily shared and referenced in the future.

## Code of Conduct
Please be respectful and constructive in all interactions. This project is a collaborative learning environment.
