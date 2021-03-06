---
title: Posts
date: 2015-11-03 08:01:00 -05:00
layout: page
weight: 2
---

Posts are a bit like special documents. Siteleaf, like Jekyll, is "blog-aware" — blogging is built in by default.

Creating a post will create a Markdown file in the `_posts/` directory that will include the timestamp and date (for example, a post titled "New York" that was created on January 6th, 2016 will turn into `2016-01-06-new-york.markdown`).

## Options

### Path

The path changes the URL this post is accessible at on your site within the `/posts/` subdirectory.

### Visibility

By default, posts are visible. You can change them to hidden or draft (in which case, they'd be moved to the `_drafts/` directory).

### Tags

Tags are a way to link common posts with each other. Separate multiple tags with a comma.

### Categories

A category is an overarching theme that a post has. Separate multiple categories with a comma.

### Date

This changes the timestamp associated with the post.

### Permalink

The permalink changes the URL this post is accessible at on your site. Unlike a path, this can change the URL to be anywhere on the site, not just under `/posts/`.

### Layout

The layout field lets you select which layout in `_layouts/` this post should use.

## Further Reading

- [Jekyll: Writing posts](http://jekyllrb.com/docs/posts/)
- [Jekyll: Working with drafts](http://jekyllrb.com/docs/drafts/)
