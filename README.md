# A03

- Installing Git

1. Install Homebrew via the command terminal using the command $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. Install **Git** via Homebrew using $ brew install git
3. Once **Git** is installed, install Webstorm via the JetBrains student license

- Using GitHub

1. Create an account (https://github.com/join)
2. Create a new **repository** via the “+” in the corner
3. When on the new **repository** page, ensure it is set to Public if it is meant to be viewed by others, and make sure the “Add README file” box is checked
4. Click create **repository**

- Using Webstorm

1. Open the preferences and under the Version Control tab, click **Git**
2. Webstorm should automatically detect the folder for **Git**
    1. If not, click “download and install”
3. Click test to check if the installation worked
4. After it’s been installed, open the **Github** Tab
5. Click “Add account” and then “Login via **Github** ”
6. When prompted click “Authenticate”
7. HIT APPLY in Webstorm to apply all changes

- Using Webstorm to open Repositories

1. Open Webstorm
2. Click “Get from VCS” to open a **repository** from **Github**
3. Click the desired **repository** and click “clone”
4. Open the desired file (in this case README.md)
5. Edit the file in the desired way
6. When done, click the little green checkmark in the corner and click “ **Commit** and **Push** ” to save the changes to **Github**
7. Make sure the **Commit** has a unique **Commit** Message
8. Check **Github** to see the changes
9. Celebrate :D

Glossary:

1. Branch: Branches allow you to make changes to a repository without affecting the entire thing.
2. Clone: Allows the file to be saved to Webstorm and then edited.
3. Commit: Changes saved to the file.
4. Fetch: Downloads files, commits, and refs from a remote repository into a local repository (6)
5. GIT: Git is an open source version control system which lets you track changes made to files
6. Github: A website that allows users to connect their files and create repositories
7. Merge: Combine multiple changes
8. Merge Conflict: When you merge branches that have different commits, there is a conflict, like two conflicting stories on the same topic. The user must resolve these changes. (5)
9. Push: Sending the changes to GitHub (1)
10. Pull: Downloads content from a repository (6)
11. Remote: Remote lets you connect to other repositories (6)
12. Repository: Collections of files in all edited states (7)

References:

1. IS 117 - IntroToGitHub-20190318 Powerpoint
2. Git: https://git-scm.com/download/mac
3. Github: https://github.com
4. Homebrew website: https://brew.sh
5. Git Definitions: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches
6. Atlassian Bitbucket https://www.atlassian.com/git/tutorials/syncing/git-fetch
7. ByGeeksForGeeks https://www.geeksforgeeks.org/what-is-a-git-repository/