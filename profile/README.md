# Suns Legacy Partners GitHub
Centralized home to all Suns/Mercury related source code.

### Creating a new repository and pushing to GitHub
Take these steps to push your source code into the Suns organization GitHub:
* Download Git https://git-scm.com/downloads
* Navigate to https://github.com/Suns-Legacy-Partners-LLC, click "New"
* Choose your repository name
* Select "Private" and "Add a README file"
    * The README is documentation on the repository in which you're creating. This includes but is not limited to:
        * How to run/execute
        * Any caveats to be aware of
        * Features
        * Creators/Authors
* In your terminal, navigate to the directory in which you wish to push to GitHub
* After you've navigated to the project directory, print these commands in the terminal:
    * ```git init``` to initiate the git repository and create the *.git* directory.
        * If this is your first time - You should be prompted to login to GitHub (Which will set your SSH profile to successfully make requests).
    * ```git status``` to see what files are staged (green) and what files are not staged (red).
    * Create a .gitignore file within the directory if there are file that you want Git to ignore see [.gitignore documentation](https://git-scm.com/docs/gitignore) for more details.
    * ```git add *``` to stage all unstaged files
        * OR add specific files ```git add path/to/unstaged/file1 path/to/unstaged/file2```
    * ```git commit -m "initial commit"``` to commit these files and/or changes when adding (or editing files down the line).
* Navigate back to https://github.com/Suns-Legacy-Partners-LLC, select your newly created repository
    * Click code
    * HTTPS > Copy the URL
* Inside your terminal:
    * ```git remote add {name of repo} {URL}```
    * ```git push --set-upstream {name of repo} main```

**Your files should now be visible within the GitHub repository**  
*This is ONLY to get started, for more information on GitHub please see documentation at https://git-scm.com/docs.*