---
title: "Welcome to WingerTries"
date: 2026-06-18 10:00:00 +1000
categories: [Meta]
tags: [intro]     # TAG names should always be lowercase
pin: true
---

This is the first post on the blog. It's also a quick demo of how writeups will
look here, so I'll show off a few of the formatting features I'll actually use.

## Code blocks

Fenced code blocks get syntax highlighting and a copy button:

```bash
# enumerate open ports
nmap -sC -sV -oN nmap/initial 10.10.10.10
```

```python
import requests

r = requests.get("https://target.example/api", timeout=5)
print(r.status_code, len(r.text))
```

## Callouts

> Reminder: only test systems you're authorized to touch.
{: .prompt-warning }

> Tip: the table of contents on the right is generated automatically from your headings.
{: .prompt-tip }

## What's next

I'll start dropping CTF writeups and pentesting notes here. To add a new post,
drop a Markdown file in `_posts/` named `YYYY-MM-DD-title.md` with front matter
like the block at the top of this file.
