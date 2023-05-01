<div id="top"></div>

## Welcome to Your Next.js + MDX Blog Starter!

This starter template is designed to get you up and running with a Next.js-powered blog that uses MDX for content. You can use this as a starting point for your own blog or as a reference for how to use Next.js and MDX together.

![Product Preview][product-preview-light]

![Product Preview][product-preview-dark]

### Getting Started

To get started, clone the repository and install the dependencies:
Edit the source code in the /pages and /components directories.

### Writing Blog Posts

Blog posts go in the **/posts** directory. To create a new blog post, create a new file in this directory using the **.mdx** file extension. The file name will be used as the URL for the blog post, so choose a descriptive and meaningful name.

In the front matter of the blog post, you can set various metadata such as the title, author, and date:

```
---
title: My First Blog Post
tags:
  - nextjs
  - reactjs
date: 2022-12-30
excerpt: Some excerpt
image: '/image-location'
---
```

After the front matter, you can write the body of the blog post using MDX syntax. MDX is a format that allows you to write both Markdown and JSX in the same file, so you can include React components in your blog posts.

### Customizing the Template

You can customize the look and feel of the blog by editing the components in the **/components** directory. The main layout of the blog is in /components/layout, and the styles are in /components/styles/global.css. You can also add your own React components and use them in your blog posts.
