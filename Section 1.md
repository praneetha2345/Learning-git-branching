##SECTION-1:

#LEVEL-1[git commit]
<img width="1897" height="725" alt="Screenshot 2025-12-22 143826" src="https://github.com/user-attachments/assets/80ebcc2c-6b2e-4793-b7c3-bc6a2672c64e" />
This repository is created to understand the basic concept of Git commits using the **Learn Git Branching platform.
Commands Used:
git commit,
git commit
Commit Flow:
C0 → C1 → C2 → C3 (main)

#LEVEL-2[git branches]
<img width="1878" height="733" alt="Screenshot 2025-12-22 145255" src="https://github.com/user-attachments/assets/33b216fc-8332-4720-bd46-5d397df9eb28" />
Creating a New Branch
The following command is used:
git checkout -b bugFix
This single command does two things:
Creates a new branch named bugFix
Switches (checks out) to the bugFix branch
Branch Pointers After Command Execution
Both main and bugFix branches point to the same commit (C1)
The * symbol indicates the current active branch
In the image:
bugFix* → active branch
main → inactive branch
