# Minimal Writer’s Blog (GitHub Pages + Jekyll Minima)

## 1) Create the repo
- Name it exactly: `<yourusername>.github.io` (replace with your GitHub username).

## 2) Push these files
- Upload the contents of this folder to the repo root.
- Commit to `main` (default).

## 3) Turn on Pages (if needed)
- Settings → Pages → Source: `Deploy from a branch`
- Branch: `main` → `/ (root)`

## 4) Wait for the build
- Your site will appear at `https://<yourusername>.github.io`.

## 5) Optional: Custom domain
- Buy a domain and point a CNAME record at `<yourusername>.github.io`.
- Add a `CNAME` file in the repo containing your domain (e.g., `blog.yourname.com`).

## 6) Write posts
- Create files under `_posts/` named like `YYYY-MM-DD-title.md` with front matter:
```
---
layout: post
title: "Your post title"
description: One-line summary
date: 2025-10-17 10:00:00 +0530
categories: notes
---

Your markdown here.
```
- Commit → it shows up on the homepage automatically.

## 7) RSS
- Your feed is at `/feed.xml` (thanks to `jekyll-feed`).

## 8) SEO
- `jekyll-seo-tag` is included; update `_config.yml` with `url:` once deployed.