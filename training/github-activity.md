# GitHub Activity 🛠️

## 1. Clone a repo

1.  Open the [GitHub repository](https://github.com/Metal-subsidy-stress/github-playground)
2.  Click Green "\<\> Code" box and select "Local"
3.  Select either HTTPS or SSH (depending on your setup) and copy the link
4.  Open RStudio and select "Project: None" -\> "New Project"
5.  Select "Version Control" -\> "Git" -\> and paste the link to the "Repository URL" box
6.  Give the directory a unique name in "Project directory name"
    -   This will be the folder name on your local machine
7.  Select a directory where this folder will live
    -   I recommend you do **NOT** use a cloud location (e.g., Google Drive, OneDrive) as the duplicate version control can cause issues
8.  Click "Create project" to finish setup

## 2. Create a file on GitHub.com

1.  Return to the GitHub repository on your browser
2.  Navigate to **training** directory
3.  On top-right corner, click *Add file* \> *Create new file*
4.  Type your *first name* and “.txt” on the *Name your file* box
5.  Type your *last name* as the file content
6.  Scroll down and type a **commit message** + **extended description**

## 3. Pull from remote repo

1.  Return to RStudio
2.  In the "Environment" pane click on the "Git" tab
3.  Click "Pull" to download any changes to the repository from the remote

## 3. Create a file on local directory

1.  Create or find a simple text file, csv, or script, and drag the file into the **training** directory on your local machine
2.  In RStudio, you'll notice the new file in Git section with two question mark boxes in the Status column
3.  To send this file to the remote repository select the "Staged" box for the file you wish to upload
    -   You'll notice the Status box changes to "A" which means you are adding a new file
4.  Once staged, click the "Commit" and a new window will open
5.  The bottom of the Commit window highlights the changes in the file. Add a description of the "Commit message" box describing the changes.
    -   Advice for using Git is to commit often. View this as similar to clicking *Save* when you are writing a document.
6.  Click the "Commit" button to finalize your commit
    -   The Commit you have just done is still on your local machine. You will need to "Push" the changes to send them to the remote.
7.  Click "Push" to send your file to the remote repo

## 5. Working on the same code - branching

1.  When you may have multiple people working on the same file it is best to create your own Branch to work locally on changes and not affect others
2.  In RStudio click the "New Branch" button and give it a unique name.
    -   Now you can all work on a unique "branch" of the same code without disrupting the *Main* code or generating conflicts with your collaborators
3.  Open the file `test-function.R`
4.  Change the text
5.  Navigate to **Pull requests** tab (up top) and click on **New pull request** (green button, right side)
6.  Under **Compare** select your new branch
7.  GitHub will show you the **diffs**
8.  Select *Create pull request*
9.  GitHub checks whether your `new branch` and `main` can be merged automatically (without any conflicts)
10. If everythig looks good, click *Confirm merge*

-   You can delete your branch or keep it if you will continue working on a specific task.
-   You can leave detailed comments, refer issues, tag individuals, and add lists of tasks within each pull request.
