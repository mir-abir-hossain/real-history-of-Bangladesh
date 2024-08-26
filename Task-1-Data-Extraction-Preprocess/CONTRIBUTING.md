# Contributing to Data Extraction and Preparation
This guide will give you general instructions on how to contribute to the data extraction, cleanup, and preparation process.

## How to Request to be Assigned to an Issue
1. Click on the Issues tab and take a look at the open issues labelled **data**.
2. If you find something that you want to work on, leave a comment showing your interest and tag the project lead, team lead, and/or tech lead. One of them will assign you the task.
3. After you are assigned a task, you can start working on it.
4. Assignments will be on a first-come-first-serve basis. We request you not to start working on an issue before you are assigned to it.
5. Feel free to show interest even if you are not the first person to do so. Depending on the length or difficulty, one task may require multiple contributors to finish.

## How to Commit Your Work
1. If this is your first issue, you need to fork the repository first. From the main page of the GitHub repository, click 'Fork' to fork it. Uncheck the option 'Copy the main branch only' and click 'Create fork'. If this isn't your first issue, proceed to step 3.
2. Clone the forked repository to your local machine and open it using the terminal/command line or with your favourite IDE.
3. Switch to the **dev** branch: `git checkout dev`
4. If this isn't your first issue (i.e. you're already working on the clone of your forked repo), run the command `git pull` to pull the latest code from the **dev** branch.
5. Now, create a new branch. Name it using the following convention: **data_<your_github_username>_<one_or_two_words_on_the_issue>**. For example, if your GitHub username is **user123** and you are working on cleaning the file **sample_1.txt**, you can use the following branch name: **data_user123_sample1_cleanup**. You can name your branches differently as long as you start with **data_<your_github_username>_**
5. Push your work to this branch.

## Create a Pull Request (PR)
1. After pushing your work, create a pull request to the **dev** branch. You can create a PR online from your GitHub account or using the GitHub CLI (terminal or command line). The base branch should be **dev**. DO NOT create a PR to the **main** branch.
2. A tech lead or team lead will review your PR and merge it if everything looks okay. You can also ask someone to review your PR through the 'Reviewers' tab on your right.
3. Congratulations and thank you!

## File Naming Conventions
1. For data cleanup tasks, add the suffix '_clean' to the filename. For example, if the filename is 'sample_1.txt', the cleaned filename should be 'sample_1_clean.txt'. Try not to leave any space in the filename.