# The GitHub Treasure Hunt

Welcome, adventurer! ... (Introductory text)

## Level 1: Forking the Repository

A journey begins with a copy... (Clue)

**Task:** Fork this repository.

**Treasure:** `part1.txt` (already present).

**Instructions:** Fork this repository by clicking the "Fork" button.
## Level 2: Cloning the Repository

Bring the treasure map to your local grounds. Only then can you truly explore.

**Task:** Clone your forked repository.

**Treasure:** A hidden directory `.hidden_treasure` contains `part2.txt`.

**Instructions:** Clone your forked repository using: `git clone <your_forked_repo_url>`. Use `ls -a` to see hidden files and directories.

## Level 3: Creating a Branch and Making a Change

A new path may lead to new discoveries. Branch out and leave your mark.

**Task:** Create a new branch, add a file with your username, and commit.

**Treasure:** The commit message contains `part3.txt`.

**Instructions:**
1.  Create a new branch: `git checkout -b treasure-hunt`.
2.  Create a file: `touch found.txt`
3. Add your GitHub username to the file: `echo "YourGitHubUsername" > found.txt`
4. Add and commit:
    ```bash
    git add found.txt
    git commit -m "Found the next piece! Part 3: IS"
    ```
Use `git log` to find the treasure in the commit message.
