---
layout: post
title: "Helpful Git Commands"
date: 2017-05-05
category: "Dev"
tags: [git]
comments: true
---
I've decided to keep a dump of helpful git commands I come across for reference.

`git push origin :old_branch new_branch`

This command will push the deletion of `old_branch` and the creation of `new_branch`

---

`git reset [--<soft|mixed|hard>] branch`

- `--soft` - Current changes remain and are staged
- `--mixed` - Current changes remain but are not staged
- `--soft` - Current changes do not remain

---
