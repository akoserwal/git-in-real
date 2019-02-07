# Git-in-Real: Lesson 1

Remotes: Adding a remote location to where you can publish your repository. You can add mutiple remote location. 

### To Check remote locations

```git remote -v```

### Ouput:

```
origin  https://github.com/akoserwal/git-in-real.git (fetch)
origin  https://github.com/akoserwal/git-in-real.git (push)
```

### Add a remote location

Name of remote location can be any thing based on your use-case & ease of use. 

```
git remote add ch1-remote-origin https://github.com/akoserwal/git-in-real.git 
```

#### Verify 

```git remote -v```

### Push your local repository branch to remote location

``` 
git push ch1-remote-origin ch1-remotes-final
```

