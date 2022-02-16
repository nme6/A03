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
      - Ctrl + K, add your **commit** message, and hit **Commit**.
   3) To **push** the changes you made to your GitHub:
      1) 