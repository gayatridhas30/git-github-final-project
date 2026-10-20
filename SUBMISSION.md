# FINAL PROJECT — COMPLETE SUBMISSION (All 9 Tasks)

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

### Task 6 (2 points) — forked-repo

```
$ curl -s https://api.github.com/repos/gayatridhas30/mcino-Introduction-to-Git-and-GitHub | grep -E '"(full_name|fork)":'
  "full_name": "gayatridhas30/mcino-Introduction-to-Git-and-GitHub",
  "fork": true,
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false,
    "full_name": "ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub",
    "fork": false,
```

### Task 7 (2 points) — merge_branches

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

### Task 8 (2 points) — bug-fix-revert

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

### Task 9 (2 points) — github-branches

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
