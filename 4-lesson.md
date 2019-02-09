# Git-in-Real: Lesson 4

# Rebase: Rewriting history with a sequence of commits.

This is most common case while working with in a team.

You and your teammate started working on a same project/repository. You checkout a branch `Ch4-rebase` and your team mate `Ch4-feature` from the same starting point. You both started working on adding some features. Now problem comes when we want to merge those changes back into the repository. If you merged your changes first. When your teammate try to merge back. He/she will get the merge conflicts. 
Resolving conflicts are not very fancy part of this process. 

### Rebase comes to your rescue!!


Let's take a real life example. You and your teammate started running from a point A to B and finishes at point C with a stick. Rule is to delivery the stick, but both should handle the stick during the travel in a equal amount of time interval. 

While running you and your team mate would be in a confusion when I should pass the stick to another person.

Better approach would be

What if your team already have a head-start, He waits for your at point B. That's what we call a relay race. 

Same way `git rebase` will allow your team mate to re-write history and gets a head start. 










