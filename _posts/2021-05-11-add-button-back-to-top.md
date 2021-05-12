---
title:  "Add button Back to top  "
date:   2021-05-11 00:00:00 +0100
toc: true
toc_label: "My Table of Contents"
toc_icon: "cog"
toc_sticky: true
header:
    # teaser: "/assets/images/500x300.png"
    overlay_image: assets/images/unsplash-gallery-image-2-th.jpg
categories:
  - blog
  - Jekyll
tags:
  - tips
  - web
excerpt: Add button Back to top 
---
## Intro
This is a simple way to integrate the button Back-to-top into a jekyll website
## First Step
Inspired by this Repo
Add button Back to top 
https://github.com/vfeskov/vanilla-back-to-top
### First step. First move
Add to this file
**_includes\scripts.html**
```html
<script src="https://unpkg.com/vanilla-back-to-top@7.2.1/dist/vanilla-back-to-top.min.js"></script>
<script>addBackToTop({
  diameter: 56,
  backgroundColor: 'rgb(255, 82, 82)',
  textColor: '#fff'
})</script>
```
### First step. Second move
How to modify
https://github.com/vfeskov/vanilla-back-to-top/blob/v7.2.1/EXAMPLES.md