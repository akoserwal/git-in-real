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





