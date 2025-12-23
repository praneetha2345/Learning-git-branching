# Learning-git-branching
learning git branching by using commits

# SECTION-1:

# LEVEL-1[git commit]
<img width="1897" height="725" alt="Screenshot 2025-12-22 143826" src="https://github.com/user-attachments/assets/80ebcc2c-6b2e-4793-b7c3-bc6a2672c64e" />

This repository is created to understand the basic concept of Git commits using the **Learn Git Branching platform.

```

git commit

git commit

```

# Commit Flow:

C0 → C1 → C2 → C3 (main)

# LEVEL-2[git branches]

<img width="1878" height="733" alt="Screenshot 2025-12-22 145255" src="https://github.com/user-attachments/assets/33b216fc-8332-4720-bd46-5d397df9eb28" />

Creating a New Branch

# The following command is used:
```

git checkout -b bugFix

```

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
```

git checkout -b bugFix

git commit

git checkout main

git commit

git merge bugFix

```

# LEVEL-4:[branching rebase]

<img width="1507" height="569" alt="Screenshot 2025-12-17 110004" src="https://github.com/user-attachments/assets/8a530d76-55e5-41dc-a01a-8e637797db03" />


## Commands Used
```

git branch bugFix

git checkout bugFix

git commit

git checkout main

git commit

git checkout bugFix

git rebase main

```

# SECTION -2:

# LEVEL-1:

<img width="1909" height="827" alt="Screenshot 2025-12-17 110219" src="https://github.com/user-attachments/assets/40c61b71-1507-48b0-aac0-4f6f216118a0" />
```

git checkout C4

```

# LEVEL-2:

<img width="1910" height="752" alt="Screenshot 2025-12-17 110352" src="https://github.com/user-attachments/assets/cbef9ff5-6676-470e-9c03-1107743da901" />

```

git checkout HEAD^

```

# LEVEL-3:

<img width="1877" height="740" alt="Screenshot 2025-12-17 111220" src="https://github.com/user-attachments/assets/48a56f5b-6207-4e52-b523-4e996effeee9" />

git checkout HEAD~1

git branch -f bugFix C0

git branch -f main C6

# LEVEL -4:


<img width="1893" height="786" alt="Screenshot 2025-12-17 112207" src="https://github.com/user-attachments/assets/d5ede02b-4be8-4466-abdd-aabbc0f1e38d" />

```

git reset HEAD~1

git checkout local

git checkout main

git checkout main

git checkout pushed

git revert pushed

```

