Objective

To convert a local project into a Git repository and understand the basic Git commands.

1. Introduction

Git is a version control system used to track changes in files and manage project history. It helps developers maintain different versions of their code.

2. Installing and Verifying Git

Git installation can be verified using the following command:

git --version

This command displays the installed Git version.

3. Initializing a Git Repository

The following command initializes a Git repository inside the project folder:

git init

4. Configuring Git Username and Email

Git username and email can be configured using these commands:

git config --global user.name "Shubham Yadav"
git config --global user.email "your-email@example.com"

5. Creating an HTML File

An HTML file named index.html was created with the following code:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Git Project</title>
</head>
<body>
    <h1>Welcome to My Web Development Project</h1>
    <p>This is my first webpage using HTML and Git.</p>

    <section>
        <h2>About This Project</h2>
        <p>I am learning web development and Git basics.</p>
    </section>

    <footer>
        <p>Created as part of Assignment 1.4</p>
    </footer>
</body>
</html>

6. Basic Git Commands

Check repository status:

git status

Add the HTML file to the staging area:

git add index.html

Save changes in the repository:

git commit -m "Initial commit: Create HTML webpage"

7. Creating Three Meaningful Commits

The following three commits are required:

Commit 1: Create the basic webpage

git add index.html
git commit -m "Initial commit: Create HTML webpage"

Commit 2: Add project information

After adding the About section to the HTML file:

git add index.html
git commit -m "Add project information section"

Commit 3: Add a footer

After adding the footer to the HTML file:

git add index.html
git commit -m "Add footer to webpage"

To view the commit history, use:

git log --oneline

8. Result

A local Git repository was initialized, Git username and email were configured, an HTML webpage was created, and three meaningful commits were planned to track project changes.

9. Conclusion

This assignment explains how to initialize a Git repository, configure Git, create an HTML file, check repository status, stage files, commit changes, and view commit history.

10. Screenshots

The following screenshots should be attached as proof of completion:

Git version verification using git --version.

Project folder containing index.html.

Git repository status using git status.

Commit history showing three commits using git log --oneline.