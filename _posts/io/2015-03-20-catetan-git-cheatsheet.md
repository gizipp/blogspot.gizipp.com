---
layout: post
title: "Catetan Git (Cheatsheet)"
shorttitle: "Catetan Git (Cheatsheet)"
desc: "Catetan Git cheatsheet kalau-kalau lupa-lupa ingat."
category: io
tags: [git]
---

## Hapus Branch Remote

Hapus branch remote yang sudah tidak dipakai alias sudah merged ke master/prod

    git push origin --delete 11-nama-branch

## Hapus Branch Lokal

{% comment %}{% include ads.html %}{% endcomment %}

Hapus branch local yang sudah tidak dipakai alias sudah merged ke master/prod

    git branch -D 11-nama-branch

## Tautan

- http://git-scm.com/book/en/v2/Git-Branching-Remote-Branches