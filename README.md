# Useful Git Commands

## Clone the repository

Download the project to your local machine:

``` bash
git clone <repository-url>
```

## Create a new branch

Create and switch to a new branch:

``` bash
git checkout -b <branch-name>
```

## Stage changes

Add all changed files to be included in the commit:

``` bash
git add .
```

## Commit changes

Save your changes with a meaningful message:

``` bash
git commit -m "Your commit message"
```

## Push branch to GitHub

Push your branch to the remote repository:

``` bash
git push --set-upstream origin <branch-name>
```

------------------------------------------------------------------------

## Typical Workflow

1.  Clone the repository\
2.  Create a new branch\
3.  Make your changes\
4.  Add and commit changes\
5.  Push the branch\
6.  Open a Pull Request on GitHub

## Rules

### Branch Name

For new tests use: feature/<JIRA-Task-Id>-<developer-credentials>
For bugs in existing tests use: bug/<JIRA-Task-Id>-<developer-credentials>