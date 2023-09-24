---
title: "Test"
date: 2023-09-24T15:19:48+02:00
author: Leon
tags: ["put", "some", "tags", "here"]
categories: ["catgorized", "the", "page"]
description: "Description of this page."
keywords: "keywords,used,for,SEO"
draft: false
math: true
---

Header
------

# Grosser Titel

## Mittlerer Titel

### Kleiner Titel

### Snippet

```python
import os
import subprocess
import shutil
from pathlib import Path
from datetime import datetime, timezone, timedelta
import yaml
import git
import time


def fetch_and_copy(git_dir, target_dir):
    os.chdir(git_dir)

    print(f"--- fetch updates {git_dir} ---")

    repo = git.Repo(git_dir)

    subprocess.run(["git", "fsck"])
    subprocess.run(["git", "gc", "--prune=now"])

    print("|- git reset")
    repo.git.reset('--hard')
    time.sleep(1)
```

### LaTex

$\Omega$

[Link](www.strubli.com)

![Bild](https://assets.tina.io/2c8d8b94-5c46-4d05-8458-41056374a05a/posts/cable-car-cabin.gif)
