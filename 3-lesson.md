# Git-in-Real: Lesson 3

# Merge-Conflicts

You will encounter conflict when working within in a team or even working on your own project. 

Let's create a conflicting situation and confuse the git system.

```git checkout Ch3-conflict```

Now try to update the `3-lesson` file.

Once you made the changes.

```git add 3-lesson```

and stage the file.

```git commit -m "updating lesson-3"```


Now,

```git checkout Ch3-merge```


and try to merge the conflict branch.

```git merge Ch3-conflict```

You will see a message about merge conflict.

Merge conflict occurs when we are try to confuse the git system by merging changes which acts as counter to each other. Like in this case.

In the console, you will see message like this:

```
Auto-merging 3-lesson.md
CONFLICT (content): Merge conflict in 3-lesson.md
Automatic merge failed; fix conflicts and then commit the result.

```

Open the file in the editor and you can see the conflict 


```
<<<<<<< HEAD (Current Changes)
```git merge origin/Ch3-conflict```

You will see a message about merge conflict.

Merge conflict occurs when we are try to confuse the git system by merging changes which acts as counter to each other. Like in this case. 


=======
By giving a merge conflict. it gives the controll in hands of user.
>>>>>>> Ch3-conflict (Incoming Changes)

```

You can remove the changes either keep the `Current Changes` or `Incoming changes`. Based on your understanding.
`
Save and try

     `git status`

You can see the message
```

On branch Ch3-merge
Your branch is up-to-date with 'origin/Ch3-merge'.
You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
```

If you are not sure with the changes. you use can `git merge --abort` to abort the merge process and re-think.

And if you are sure. then go ahead by commiting the changes.


