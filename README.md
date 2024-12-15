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

## Level 4: Creating a Pull Request

Share your findings with the world. A request for integration is the final step.

**Task:** Create a pull request from your `treasure-hunt` branch.

**Treasure:** `part4.txt` will be revealed after the PR is merged.

**Instructions:**
1. Push your branch: `git push origin treasure-hunt`
2. Create a pull request on GitHub to the original repository.

Once the PR is merged, the final piece will appear in the main branch.
