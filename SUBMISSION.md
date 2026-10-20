# FINAL PROJECT — COMPLETE SUBMISSION (All Tasks)

**Student:** Gayatri Dhas (GitHub: gayatridhas30)
**Repository:** https://github.com/gayatridhas30/git-github-final-project

---

## PART 1 — GitHub UI (12 points)

### Task 1 (4 points) — README.md URL
```
https://github.com/gayatridhas30/git-github-final-project/blob/main/README.md
```

### Task 2 (2 points) — LICENSE (Apache 2.0) URL
```
https://github.com/gayatridhas30/git-github-final-project/blob/main/LICENSE
```

### Task 3 (2 points) — CODE_OF_CONDUCT URL
```
https://github.com/gayatridhas30/git-github-final-project/blob/main/CODE_OF_CONDUCT.md
```

### Task 4 (2 points) — CONTRIBUTING.md URL
```
https://github.com/gayatridhas30/git-github-final-project/blob/main/CONTRIBUTING.md
```

### Task 5 (2 points) — simple-interest.sh URL
```
https://github.com/gayatridhas30/git-github-final-project/blob/main/simple-interest.sh
```

---

## PART 2 — Git CLI (8 points)

### Part 2 Task 1 (2 pts) — URL of the forked repository
```
https://github.com/gayatridhas30/mcino-Introduction-to-Git-and-GitHub
```

### Part 2 Task 2 (2 pts) — Screenshot of the first merge
**File to upload:**
```
D:\git-github-final-project\merge-screenshot.png
```
(also copied to Desktop: `C:\Users\Gayatri Dhas\OneDrive\Desktop\merge-screenshot.png`)

The screenshot shows a live terminal replay of the real merge:
- `git checkout main` → Switched to branch 'main'
- `git merge bug-fix-typo` → `Updating ad95b0a..bdad08f` / `Fast-forward` / `simple-interest.sh | 2 +-` / **`1 file changed, 1 insertion(+), 1 deletion(-)`**

### Part 2 Task 3 (2 pts) — URL of the pull request
```
https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/12643
```
(The PR was opened from fork `gayatridhas30/mcino-Introduction-to-Git-and-GitHub`.
The repo's `close_pr.yml` bot auto-closes it with: "Congratulations! You have completed
the lab. Closing for maintainence purpose." — this is the lab's designed behaviour.)

### Part 2 Task 4 (2 pts) — URL of the Branches page
```
https://github.com/gayatridhas30/mcino-Introduction-to-Git-and-GitHub/branches
```
(Displays `main` and `bug-fix-typo` with their up-to-date status.)

---

## Supporting evidence (terminal outputs, also in this repo)

### forked-repo
```
$ curl -s https://api.github.com/repos/gayatridhas30/mcino-Introduction-to-Git-and-GitHub | grep -E '"(full_name|fork)":'
  "full_name": "gayatridhas30/mcino-Introduction-to-Git-and-GitHub",
  "fork": true,
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false,
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false,
```

### merge_branches
```
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

$ git merge bug-fix-typo
Updating ad95b0a..bdad08f
Fast-forward
 simple-interest.sh | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)
```

### bug-fix-revert
```
$ curl -s https://api.github.com/repos/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pulls/12643 | grep -E '"(html_url|state|full_name|merged)":'
  "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/12643",
  "state": "closed",
    "html_url": "https://github.com/gayatridhas30",
      "full_name": "gayatridhas30/mcino-Introduction-to-Git-and-GitHub",
        "html_url": "https://github.com/gayatridhas30",
      "html_url": "https://github.com/gayatridhas30/mcino-Introduction-to-Git-and-GitHub",
      "html_url": "https://github.com/gayatridhas30",
      "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
        "html_url": "https://github.com/ibm-developer-skills-network",
      "html_url": "https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
      "html_url": "https://github.com/ibm-developer-skills-network",
  "merged": false,
```

### github-branches
```
$ git branch -a
  bug-fix-typo
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/bug-fix-typo
  remotes/origin/main
```

---

## Links
- Public repo: https://github.com/gayatridhas30/git-github-final-project
- Fork of IBM repo: https://github.com/gayatridhas30/mcino-Introduction-to-Git-and-GitHub
- Pull request: https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub/pull/12643
- Branches page: https://github.com/gayatridhas30/mcino-Introduction-to-Git-and-GitHub/branches
