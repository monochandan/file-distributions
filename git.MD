# If I want to rewmove pushed folder from any repo, after i have pushed already (in this case /rag was pushed, now i want to remove from the repository)
```
git rm -r --cached rag
git add .gitignore
git commit -m "Remove folder from repository"
git push

```
