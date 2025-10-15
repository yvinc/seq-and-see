# To use Git-lfs ( Large File Storage ) to push large files to Github

1.  In terminal, initialize Git LFS in current repo's working path:

```         
git lfs install
```

2.  Git reset commits if necessary:

```         
git reset --soft HEAD~1
```

3.  Select file types (e.g., `*.csv`) that you want Git LFS to track. This creates a .gitattribute file in the parent folder:

```         
git lfs track “*.csv”
```

4.  Then we commit & push:

```         
git commit -m "This is a commit message"
```

```         
git lfs push --all origin
```

4.  If the above steps doesn't work, the large file likely isn't properly tracked by Git LFS. To debug, run `git lfs migrate`:

```         
git lfs migrate import --include="*.csv,*.tsv" --everything
```

6.  Commit & Push again

```         
git commit  -m "This is a commit message"
```

```         
git lfs push --all origin
```

```         
git push
```

8.  Check remote repo to see if file is pushed successfully.