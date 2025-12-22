# SECTION-1:

# LEVEL-1[git commit]
<img width="1897" height="725" alt="Screenshot 2025-12-22 143826" src="https://github.com/user-attachments/assets/80ebcc2c-6b2e-4793-b7c3-bc6a2672c64e" />

This repository is created to understand the basic concept of Git commits using the **Learn Git Branching platform.

# Commands Used:
git commit,

git commit

# Commit Flow:

C0 → C1 → C2 → C3 (main)

# LEVEL-2[git branches]

<img width="1878" height="733" alt="Screenshot 2025-12-22 145255" src="https://github.com/user-attachments/assets/33b216fc-8332-4720-bd46-5d397df9eb28" />

Creating a New Branch

# The following command is used:

git checkout -b bugFix
This single command does two things:

Creates a new branch named bugFix
Switches (checks out) to the bugFix branch
Branch Pointers After Command Execution

Both main and bugFix branches point to the same commit (C1)

The * symbol indicates the current active branch

bugFix* → active branch

main → inactive branch

# LEVEL-3[branches merging]

<img width="1890" height="726" alt="Screenshot 2025-12-22 150311" src="https://github.com/user-attachments/assets/83fc9399-0408-4246-8a78-290d72132187" />


This repository demonstrates the concept of merging branches in Git using the Learn Git Branching interactive platform



## Commands Used

git checkout -b bugFix

git commit

git checkout main

git commit

git merge bugFix

# LEVEL-4:[branching rebase]

<img width="1507" height="569" alt="Screenshot 2025-12-17 110004" src="https://github.com/user-attachments/assets/8a530d76-55e5-41dc-a01a-8e637797db03" />


## Commands Used


git branch bugFix

git checkout bugFix

git commit

git checkout main

git commit

git checkout bugFix

git rebase main

Step-by-Step Flow Explanation

1. Initial Commit

The repository begins with an initial commit:

C0 → C1

2. Create and Switch to bugFix Branch

git branch bugFix

git checkout bugFix


A new branch bugFix is created

Work starts on the bugFix branch

3. Commit on bugFix
git commit


A new commit C2 is created on bugFix

C1
 └─ C2 (bugFix)

4. Switch to main and Commit

git checkout main

git commit


A new commit C3 is added to main

C1
 ├─ C2 (bugFix)
 └─ C3 (main)

5. Rebase bugFix onto main
   
git checkout bugFix

git rebase main


Git moves bugFix commits on top of main

Commit C2 becomes C2'

History becomes linear

Final Commit Structure
C0 → C1 → C3 → C2' (bugFix)


main remains at C3

bugFix is replayed after main

