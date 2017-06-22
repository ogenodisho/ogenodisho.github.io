---
layout: post
title: "Helpful Git Commands"
date: 2017-05-05
categories: [Dev]
tags: [git]
comments: true
---

I've decided to keep a dump of helpful git commands I come across for reference.

```
git reset [--<soft|mixed|hard>] branch

  --soft - Current changes remain and are staged
  --mixed - Current changes remain but are not staged
  --soft - Current changes do not remain  
```

```
git <...> --no-verify

  Bypasses any git hooks
```

```
git -xfd

  Removes all files ignored by Git from your working tree. Useful for rebuilding everything from scratch but keeping manually created files.
```

```
git -Xfd

  Removes all untracked files from your working tree.
```

The difference between the two above commands is that it is possible for a file/directory to be untracked but not ignored.

```
git check-ignore --verbose <file>

  Finds which .gitignore is causing your file to be ignored
```
