# My Blog

A personal blog powered by Jekyll and GitHub Pages.

## Setup

1. Clone this repository
2. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```
3. Install dependencies:
   ```
   bundle install
   ```
4. Run locally:
   ```
   bundle exec jekyll serve
   ```
5. Visit `http://localhost:4000/blog` in your browser

## Adding New Posts

To add a new post, create a new file in the `_posts` directory with the following format:

```
YYYY-MM-DD-title-of-post.md
```

And include the front matter at the top:

```yaml
---
layout: post
title: "Your Post Title"
date: YYYY-MM-DD HH:MM:SS -0000
categories: category1 category2
---
```

Then write your content in Markdown below the front matter.

## Deployment

This blog is configured to deploy automatically to GitHub Pages. Simply push changes to the main branch, and GitHub will build and deploy the site.

To set up GitHub Pages:

1. Go to your repository settings
2. Navigate to "Pages" section
3. Set the source to "main" branch
4. Set the folder to "/ (root)"
5. Click "Save"

Your blog will be available at `https://yourusername.github.io/blog`
