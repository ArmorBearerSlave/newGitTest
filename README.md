# newGitTest
## Tutorial

### Step 1

Clone the repository into two folders on your local machine using the following command.

D:\Source Control Tutorial\Test_Folder_1>git clone https://github.com/ArmorBearerSlave/newGitTest.git

### Step 2

Navigate to the directory of your first and second folder in different CLIs.  Using the change directory command:

D:\Source Control Tutorial\Test_Folder_1>cd newGitTest

### Step 3

Create an HTML file in each folder named "index.html" and "index2.html", respectively.

### Step 4

Use the git command "git status" in the CLI.

D:\Source Control Tutorial\Test_Folder_1\newGitTest>git status

#### Result
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

### Step 5

Use the git command "git add" to add the first file "index.html" to be committed.

D:\Source Control Tutorial\Test_Folder_1\newGitTest>git add index.html

### Step 6

Check the status.

(base) D:\Source Control Tutorial\Test_Folder_1\newGitTest>git status

#### Result

On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   index.html

### Step 7

(base) D:\Source Control Tutorial\Test_Folder_1\newGitTest>git commit -m "added index.html"

#### Result

[master fe3025f] added index.html
 1 file changed, 11 insertions(+)
 create mode 100644 index.html
 
 ### Step 8

(base) D:\Source Control Tutorial\Test_Folder_1\newGitTest>git push

#### Result

Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 357 bytes | 178.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ArmorBearerSlave/newGitTest.git
   687a78b..fe3025f  master -> master



