# GitHub Push Instructions

The GitHub Personal Access Token has expired. Please use one of these methods:

## Option 1: Update Token (Quickest)

1. Generate new token at: https://github.com/settings/tokens
   - Scope: `repo` (full control)
2. Run:
```bash
cd /workspace/group/chabad-library-books-git
git remote add origin https://zmabraham:NEW_TOKEN@github.com/zmabraham/chabad-library-books.git
git push -u origin main
```

## Option 2: Manual GitHub Setup

1. Create repo at: https://github.com/new
   - Name: `chabad-library-books`
   - Public
   - Don't initialize

2. Push:
```bash
cd /workspace/group/chabad-library-books-git
git remote add origin https://github.com/zmabraham/chabad-library-books.git
git push -u origin main
```

## What's Included

- 1,782 files committed
- 84 books from Chabad Library
- 726 parts/volumes
- 725 Hebrew pages

## Repository Will Be At

https://github.com/zmabraham/chabad-library-books
