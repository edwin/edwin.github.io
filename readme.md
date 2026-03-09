# My Jekyll Blog

Personal blog hosted on GitHub Pages, built with Jekyll.

🌐 **Live site:** [https://edwin.github.io](https://edwin.github.io)

## Local Development

### Prerequisites
- Ruby >= 2.7
- Bundler

### Setup

```bash
# Install dependencies
bundle install

# Start local server (with live reload)
bundle exec jekyll serve --livereload

# Preview including draft posts
bundle exec jekyll serve --drafts
```

Visit `http://localhost:4000` in your browser.

## Writing a Post

1. Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`
2. Add front matter at the top:

```markdown
---
layout: post
title: "Your Post Title"
date: 2026-03-09 10:00:00 +0700
categories: [general]
tags: [tag1, tag2]
---

Post content here...
```

3. Commit and push — GitHub Pages will build and publish automatically.

## Drafts

Add unfinished posts to `_drafts/` (no date needed in filename).  
Preview with: `bundle exec jekyll serve --drafts`  
When ready, move to `_posts/` with the date prefix.

## Deployment

Push to `main` branch. GitHub Pages auto-builds and deploys.
