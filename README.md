# new-project

This repository uses a **development** branch for feature work.
Follow the steps below to create the branch, commit changes, and merge into **main**.

## Quickstart
```bash
# fetch
git fetch origin

# create & switch to development
git checkout -b development

# add your changes (example: README already exists)
git add README.md
git commit -m "PROJ-1 #comment add developer instructions #time 10m #done"

# push development branch
git push -u origin development

# (option A) merge via PR on GitHub
# open PR: compare = development -> base = main

# (option B) merge locally
git checkout main
git pull --ff-only
git merge --no-ff development -m "merge: development -> main"
git push origin main

