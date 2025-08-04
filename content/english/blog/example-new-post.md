---
title: "How to Add Images to Your Hugo Blog Posts"
date: 2024-01-15T10:00:00+00:00
draft: false
image: "images/post/post-1.jpg"
description: "A guide on how to properly add images to your Hugo blog posts"
categories: ["Tutorial"]
tags: ["Hugo", "Images", "Blogging"]
type: "post"
---

# How to Add Images to Your Hugo Blog Posts

This is an example of how to add images to your Hugo blog posts. The image above is referenced in the front matter using the `image` parameter.

## Adding Images in Your Content

You can also add images directly in your markdown content:

![Example Image](../../images/post/post-2.jpg)

## Best Practices

1. **Use descriptive filenames**: `my-awesome-post-image.jpg` instead of `img001.jpg`
2. **Optimize images**: Compress them for web use
3. **Use consistent paths**: Keep all post images in `static/images/post/`
4. **Include alt text**: Always add descriptive alt text for accessibility

## Image Paths

- **Front matter image**: `images/post/your-image.jpg`
- **Content images**: `../../images/post/your-image.jpg` (relative to content file)

That's it! Your images will be served correctly from your Hugo site. 