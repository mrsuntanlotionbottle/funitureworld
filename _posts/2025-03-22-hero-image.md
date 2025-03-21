---
title: "Layout: Hero Image"
image: 
  path: assets/images/sample1.jpg
  caption: "Test Caption"
categories:
  - Layout
tags:
  - content
  - image
  - layout
last_modified_at: 2018-01-31T14:28:50-05:00
---

This post should display a large hero image at the top of a page.

This post tests a horizontal image using the following YAML Front Matter:

```yaml
image:
  path: /images/eder-oliveira-180877.jpg
```

Hero images can also be assigned more succinctly when `thumbnail` or `caption` are not used.

```yaml
image: /images/eder-oliveira-180877.jpg
```

Tall images will push content down the page. `1600 x 600` is a good middle-ground size to aim for.