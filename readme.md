# Github Intro
## Install Git CLI

1. Windows: [Download](https://git-scm.com/) and run the installer. Click “Next” to accept the recommended settings. This will install Git and Git Bash.  

2. macOS (choose one method):  
   - **Homebrew**: Open Terminal and run `brew install git`.  
   - **Installer**: Download the `.dmg` file from [git-scm.com](https://git-scm.com/) and drag Git to your Applications folder.  

3. Linux: Open your terminal and use your package manager. For example, on Ubuntu:  
   ```bash
   sudo apt-get install git
   ```

Ensure Git is installed by running the following command in your terminal or Git Bash:
```bash
git --version
```

This should display the installed Git version, something like `git version 2.43.1` or similar.

## What is Git
Git is a tool that helps developers track changes in their code and manage different versions of a project. Every developer has a full copy of the project on their own computer, so they can work independently. Git allows changes to be merged later, but on its own, it does not provide a central place for everyone to share their work.

## What is GitHub 
GitHub is a web-based platform that uses Git for version control. It acts as a central place where developers can share their projects, collaborate, and review each other's code. While Git manages the versions and history of your project locally, GitHub makes it easy for teams to work together and keep everyone’s changes in sync. It is the most widely used service for hosting Git repositories.

## Configuring name and email
After installing Git, you need to set up your identity so that your commits are properly attributed to you. Open your terminal or Git Bash and run the following commands, replacing the placeholders with your actual name and email address:
```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```
This means that changes you make to repositories will be associated with this name and email. More info can be found at [Github Documentation Username & Email](https://docs.github.com/en/get-started/git-basics/setting-your-username-in-git).

## Creating a GitHub Account
1. Go to [GitHub](https://github.com/) and click on "Sign up" in the upper right corner.
2. Follow the prompts to create a new account. Make sure to use your University Email, as this allows you to access student benefits via [Github Education](https://docs.github.com/en/education/about-github-education/github-education-for-students/apply-to-github-education-as-a-student).

## Connecting Git with GitHub


## Sane Github configurations (Optional)
```bash
git config --global init.defaultBranch main
```

## More Information and Resources (Optional)
- [GitHub Documentation](https://docs.github.com/en/get-started/using-github/connecting-to-github#making-more-complex-changes-in-the-browser)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [W3Schools Git Tutorial](https://www.w3schools.com/git/default.asp?remote=github)