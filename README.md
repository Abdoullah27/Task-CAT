# Task-CAT

1. Initialize the Local Repository
Open your terminal, create a new folder for your project, navigate into it, and initialize Git.

Bash
mkdir my-awesome-project
cd my-awesome-project
git init
2. Create and Stage Your Files
Create the initial files for your project. For this example, we will generate a standard README.md file, then stage it to be tracked by Git.

Bash
echo "# My Awesome Project" > README.md
git add .
3. Make a Descriptive Commit
Save your staged files into the local repository's history. A descriptive commit message clearly explains what was added or changed and why.

Bash
git commit -m "feat: initialize repository with project structure and README documentation"
4. Create the Remote Repository on GitHub
Log in to your GitHub account in a web browser.

Click the + icon in the top right corner and select New repository.

Give your repository a name (e.g., my-awesome-project).

Leave the repository completely empty. Do not check the options to add a README, .gitignore, or license.

Click Create repository.

5. Link Local and Remote Repositories
Copy the URL provided by GitHub on the next screen (it will look like [https://github.com/Username/my-awesome-project.git](https://github.com/Username/my-awesome-project.git)). Link your local repository to this remote destination.

Bash
git remote add origin <YOUR_GITHUB_REPO_URL>
6. Push Your Code to GitHub
Rename your default branch to main (the modern Git standard) and upload your local commits to the GitHub server.

Bash
git branch -M main
git push -u origin main
