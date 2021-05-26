---
title: 'Fix for Error: Unable to update local ref'
date: 2021-05-25 22:00:00 +0000
header:
  teaser: "/uploads/git_pull_unable_to_update_local_ref.png"
  overlay_image: "/uploads/git_pull_unable_to_update_local_ref.png"
categories: blog
tags:
- solution
- git
- IT
- post
- blog

---
**Problem:**

This error is returned after _git pull:_

![](/uploads/git_pull_unable_to_update_local_ref.png)

**Solution:**

    $ git gc --prune=now
    $ git remote prune origin

**To read more:**

[https://stackoverflow.com/questions/2998832/git-pull-fails-unable-to-resolve-reference-unable-to-update-local-ref](https://stackoverflow.com/questions/2998832/git-pull-fails-unable-to-resolve-reference-unable-to-update-local-ref "https://stackoverflow.com/questions/2998832/git-pull-fails-unable-to-resolve-reference-unable-to-update-local-ref")

**Explaination:**

_to be filled here_