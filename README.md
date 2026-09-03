
# biomodsquad's Website

Visit **[biomodsquad.org](https://biomodsquad.org)** 🚀

_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

## Adding news

Create a Markdown file named `YYYY-MM-DD-short-title.md` in `_posts`. The first
paragraph becomes the preview blurb automatically. A post can also set
`description` for a custom blurb and `thumbnail` for a preview image that differs
from the full-page `image`.

```yaml
---
title: Example news title
author: Your Name
image: images/news/example-hero.jpg
thumbnail: images/news/example-thumbnail.jpg
tags:
  - award
  - research
---
```

The three newest posts appear on the homepage automatically. The News page lists
all posts newest-first and groups them by year.
