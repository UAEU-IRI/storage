### Commands for pushing updates

- From the directory, open a terminal and run the following commands:
```bash
git add --all
```
```bash
git commit -m "commit message, a description explaining why a particular change was made"
```
```bash
git push origin [branch]
```
for example, if you want to push to the master branch:
```bash
git push origin master
```

### Useful commands

- Clone the online repository to the current directory
```bash
git clone [url]
```

- Pull changes from a brnach
```bash
git pull origin [branch]
```


- To see all the changes, or to see on which branch your are
```bash
git status
```

- To change to a different (must commit all changes before switching to a different branch):
```bash
git checkout [branch] 
```

### Tips:

- Creating a repository
Create it from GitHub, then clone it on your machine. If you have exsisting files, copy and paste them inside the cloned repository. Then do ```git push ... ```
- Discard local changes:
An easy way to do it is by deleting the repository on the computer (delete the folder) and reclone it again.

- Creating a branch
Easier to do it from GitHub, create a branch there, and pull the changes using ```git pull ... ```

### Understanding GitHub workflow
Follow [this](https://guides.github.com/introduction/flow/) link. It shows you how to utilize GitHub and how to effectively use it for team work.
