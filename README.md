# How to Use GitHub : written by Muhammad Aashan

GitHub is a platform for hosting and collaborating on projects using the Git version control system. This guide will walk you through the basics of using GitHub.

## Getting Started

1. **Create an Account**: If you haven't already, go to [GitHub](https://github.com/) and sign up for an account.

2. **Create a Repository**: Once you're logged in, you can create a new repository by clicking the "New" button in the upper-right corner of the screen. Give your repository a name and description, choose whether it should be public or private, and then click "Create Repository".


3. **Clone the Repository**: To work with a repository locally on your computer, you'll need to clone it. Go to the repository's page on GitHub, click the "Code" button, and copy the URL. Then, in your terminal or command prompt, use the `git clone` command followed by the repository URL.


   `git clone <repository-url>`

 ## Commands

1. **Create a Branch**: Before making any changes to the code, it's a good idea to create a new branch. This keeps your changes isolated from the main codebase until you're ready to merge them. Use the git checkout -b command followed by the branch name to create a new branch and switch to it.

  `git checkout -b <branch-name>`


2. Make Changes: Now you can make changes to the code using your preferred text editor or IDE.

Commit Changes: Once you've made your changes, you'll need to commit them to the repository. Use the git add command to stage your changes, followed by git commit to commit them. 

`git add .`

`git commit -m "Your commit message here"`

3. Push Changes: If you're working on a branch that exists remotely, you can push your changes using the git push command.

`git push origin <branch-name>`


## config

1. View Current Configuration: `git config --list`

2. Add globally user name `git config --global user.name <username>`

3. Add globally user email `git config --global user.email <useremail>`

4. remove globally your user name `git config --unset --global user.name <username>`

5. remove globally your user email `git config --unset --global user.email <useremail>`   


## Set up Git Remote 

1. **Check Remote Path :** `git remote -v`
2. **Add Remote Path :** `git remote add -origin <yourgithubpath>`


