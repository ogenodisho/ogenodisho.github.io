---
layout: post
title: "Helpful Git Commands"
date: 2017-05-05
categories: [Dev]
tags: [git]
comments: true
---
I've decided to keep a dump of helpful git commands I come across for reference.

`git branch -m old_branch new_branch`

Create a new branch that is the same as the old one.

`git push origin :old_branch new_branch`

Push the deletion of the old branch and the creation of the new one.

---

`git reset [--<soft|mixed|hard>] branch`

- `--soft` - Current changes remain and are staged
- `--mixed` - Current changes remain but are not staged
- `--soft` - Current changes do not remain
