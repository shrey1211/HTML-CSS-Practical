# Assignment 4 – Repository with at Least Three Meaningful Commits

## Aim
To create a Git repository and maintain a history of project changes using at least three meaningful commits.

## Objective
To learn how to initialize a Git repository, configure Git identity, stage files, commit changes, and view commit history.

## 1. Configure Git Identity

Git identity is configured using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

## 2. Create and Initialize the Repository

The following commands create a project folder and initialize Git:

```bash
mkdir html-css-assignments
cd html-css-assignments
git init
git branch -M main
```

## 3. Commit 1: Add the Project README

Create a README file containing the project overview and commit it:

```bash
echo "# HTML & CSS Assignments" > README.md
git add README.md
git commit -m "docs: add README with project overview"
```

## 4. Commit 2: Add Setup and Git Assignments

Add the Markdown files for Assignments 1–5 and commit them:

```bash
git add 01-*.md 02-*.md 03-*.md 04-*.md 05-*.md
git commit -m "docs: add setup & git assignments (1-5)"
```

## 5. Commit 3: Add HTML Basics Assignments

Add the HTML files for Assignments 6–10 and commit them:

```bash
git add 06-*.html 07-*.html 08-*.html 09-*.html 10-*.html
git commit -m "feat: add HTML basics assignments (6-10)"
```

## 6. View the Commit History

The following command displays the commit history in a concise format:

```bash
git log --oneline
```

## 7. Good Commit Message Rules

1. Use the present-tense imperative form, such as `add navbar`.
2. Use a suitable prefix, such as `feat:`, `fix:`, `docs:`, `style:`, or `refactor:`.
3. Keep each commit focused on one logical change.

## Result
A Git repository is initialized, and meaningful commits are created to record project changes.

## Conclusion
This assignment demonstrates the use of Git for version control, meaningful commit messages, and tracking project history.