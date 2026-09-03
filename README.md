
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

## Adding or modifying member profiles

Member profiles live in `_members` as one Markdown file per person. Update an
existing file when a member changes roles, affiliation, or bio text. Create a
new file when adding someone new.

Use a simple lowercase filename with hyphens, such as
`_members/jane-doe.md`.

```yaml
---
name: Jane Doe
image: images/jane-doe.jpg
role: phd
group: current
description: PhD Student
affiliation: Wallace H. Coulter Department of Biomedical Engineering
links:
  email: jane.doe@gatech.edu
  github: janedoe
  orcid: 0000-0000-0000-0000
---
```

Then add the member bio text below the front matter.

Notes:

- `name`, `role`, and `group` should always be set.
- `image` is used for current members on the Team page. Store the image in
  `images/` and point to it with a relative path like `images/jane-doe.jpg`.
- `group: current` shows the member in the main Team listings.
- `group: alumni` moves the member to the Alumni section.
- Common `role` values used by the site are `pi`, `postdoc`, `phd`, `ms`, and
  `undergrad`.
- `description` and `affiliation` are optional, but helpful when you want text
  more specific than the default role label.
- `links` can include items such as `home-page`, `email`, `orcid`,
  `google-scholar`, `github`, and `linkedin`.
- `aliases` can be added for alternate publication names.

When modifying a member profile:

- Update `role` if they changed positions.
- Update `group` to `alumni` when they leave the lab.
- Replace `image` if you want a new portrait.
- Edit the body text to refresh the biography, research interests, or degree
  information.

The Team page order is controlled in `team/index.md`, which groups current
members by role and shows alumni separately.
