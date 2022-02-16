# A03

## PART 1: Directions on Using Webstorm.
### Please note that instructions may vary depending on version/circumstances. This section will also cover Git & GitHub setup as well.

1) Download the latest version of **Git** from [git-scm](https://git-scm.com/downloads).
   - Note: For Windows, as of writing this, the latest release is version 2.35.1.
   - There are instructions on installing **Git** for Mac and Linux on the downloads page. Also, if you for some reason need an older version of **Git** (possibly due to corruption or something ¯&#92;&#95;(ツ)_/¯ ), they are available on both the [website](https://mirrors.edge.kernel.org/pub/software/scm/git/) and the **Git** source **repository** on [GitHub](https://github.com/git/git).
2) Find and install the downloaded **Git** file (with most, if not, all default settings).
3) Go through the process of registering as a student account on the JetBrains website to get access to the student licensed WebStorm.
4) Download the latest version of [Webstorm](https://www.jetbrains.com/webstorm/). You may also want to try downloading it through the [student license](https://www.jetbrains.com/community/education/#students) section.
5) Find and install the downloaded Webstorm file (with most, if not, all default settings).
6) Now, it's time to set up **GitHub** while both **Git** and Webstorm are installing.
   1) Go to **GitHub**'s website ([GitHub.com](https://github.com)) and register for an account.
   2) Once setup, congrats! You now have a **GitHub** account!

#### Now, it's time for the setup of all 3 of these things.
1) Start Webstorm:
   1) Go to System Preferences
   2) Select Version Control
   3) Select **Git**
   4) Enter the path to the **Git** executable. An example of my Settings is provided below.
      ![image](https://user-images.githubusercontent.com/98120877/154331984-43215c5d-3c9c-4322-82bc-f88bc2e4c32a.png)
2) In Webstorm Settings:
   1) Select the Appearance and Behavior tab
   2) Select System Settings
   3) Select Passwords
   4) In passwords, enter the **GitHub** password location. An example of my Settings in the Password section is provided below (with some censoring for information protection).
      ![image](https://user-images.githubusercontent.com/98120877/154330603-5cf7068d-686e-4598-9bf8-9564bfdf1e8d.png)
3) On **GitHub**:
   1) Click the + sign to create a new **repository**.
      1) When creating the repository
         - Make sure that the **repository** is set to Public.
         - Make sure you click the "Add a README.md file" option so that a README.md file is made with the **repository**.
4) To use the **repository** you just created on **GitHub** in Webstorm:
   1) Select VCS
   2) Select Import Version Control
   3) Select Checkout from version control
   4) Select **Git**
   5) Enter the **GitHub repository** name and the local path name (directory) on your computer.

#### You're done with setting up everything! Now for creating, adding, committing, pushing, and pulling all your files.
1) To create a file, Click File and then select HTML5 or Stylesheet (depending on which you're going to create).
2) Write/add your code and what not to the file you created.
3) When done with writing/adding your code, and you're ready to add to your **Git**:
   1) To add your code to your **Git**
      - Option 1: Press Alt+0, click the unversioned files, right-click, and click "Add to VCS".
      - Option 2: Choose the "Add to Git" option, choose the files you would like to add, and click "Add" to add the local files.
   2) To **commit** the changes you made:
      - Ctrl+K, add your **commit** message, and hit **Commit**.
   3) To **push** the changes you made to your GitHub:
      1) Ctrl+Shift+K or clicking Git in your top bar and then **Push**
      2) Click the big blue **Push** button.

Congratulations! You **pushed** your commits to GitHub and have successfully done everything you needed to do.

# PART 2: Glossary 
Note: A good chunk is directly copied and pasted from GitHub Docs own Glossary of these terms. The only one that isn't is from Simplilearn for the term "GitHub".
- **Branch**
  - A branch is a parallel version of a repository. 
  - Contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. 
  - When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
- **Clone**
  - A copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. 
  - When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. 
  - The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
- **Commit**
  - Also known as a "revision" 
  - Is an individual change to a file (or set of files). 
  - When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. 
  - Usually contain a commit message which is a brief description of what changes were made.
- **Fetch**
  - When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. 
  - Unlike git pull, fetching allows you to review changes before committing them to your local branch.
- **GIT**
  - An open source program for tracking changes in text files. 
  - Written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
- **Github**
  - GitHub is a Git repository hosting service that provides a web-based graphical interface. 
  - It is the world’s largest coding community.
- **Merge**
  - Takes the changes from one branch (in the same repository or from a fork), and applies them into another. 
  - This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. 
  - A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
- **Merge Conflict**
  - A difference that occurs between merged branches. 
  - Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. 
  - The merge conflict must be resolved before you can merge the branches.
- **Push**
  - To send your committed changes to a remote repository on GitHub.com. 
  - Example: If you change something locally, you can push those changes so that others may access them.
- **Pull**
  - When you are fetching in changes and merging them. 
  - Example: If someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.
- **Remote**
  - The version of a repository or branch that is hosted on a server, most likely GitHub.com. 
  - Remote versions can be connected to local clones so that changes can be synced.
- **Repository**
  - The most basic element of GitHub. 
  - Easiest to imagine as a project's folder. 
  - Contains all of the project files (including documentation), and stores each file's revision history. 
  - Can have multiple collaborators 
  - Can be public or private (set in Settings of the repository)

## Sources:
- [What is GitHub And How To Use It - Simplilearn](https://www.simplilearn.com/tutorials/git-tutorial/what-is-github#what_is_github)
- [GitHub glossary - GitHub Docs](https://docs.github.com/en/get-started/quickstart/github-glossary)
- [GitHub Basic Formatting - GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [JetBrains - Webstorm Docs](https://www.jetbrains.com/help/webstorm/meet-webstorm.html)
- [IS117-004 - Introduction to Github and Webstorm (new 3/24/2019) (PPT)](https://njit.instructure.com/courses/21539/modules/items/687962) 
  - Note, you can only view this if you're a student in this section or Professor Chiusano
- [IS117-004 - Extra Git/Github Installation Instructions (2/14/2020) (PPT)](https://njit.instructure.com/courses/21539/modules/items/687963) 
  - Note, you can only view this if you're a student in this section or Professor Chiusano
