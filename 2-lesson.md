# Git-in-Real: Lesson 2

# Amend: Rewriting history

While writing this lesson I commited this file and forget to add a file. Also my commit message is not correct. As you have already checked-out this branch. 
It's your responsibility to fix my lesson.

### Question in your mind! how?

```git commit --amend ```

Above command comes to your rescue.

Now, add a file

```touch test.txt```

We need to stage this file

```git add text.txt```


Let's commit and fix the last commit message.

```git commit --amend```

You will see something like below snippet based on the editor that you have set as default. I am using `vim` as default:


```
Please fix my last stupid commit message

# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
#
# On branch master
#
# Initial commit
#
# Changes to be committed:
#       new file:   test.txt
#
```

You can update the last commit message `Please fix my last stupid commit message` to something more sensible.

### Verify 

```
git log
```

Thank you for fixing my lesson commit message. You can use amend to re-write your last commit history. It can your updating some changes in the repository or updating the commit message.


