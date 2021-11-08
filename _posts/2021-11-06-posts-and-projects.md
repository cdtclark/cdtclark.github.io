---
layout: post
title:  "3. Adding posts and projects"
date: 2021-11-06
excerpt: "Learn how to add portfolio pieces and blog posts."
project: true
tags:
- GitHub
comments: true
---

## Adding posts and projects

Posts and projects both live in the `_posts` folder. The only difference is that projects have the line `project: true` in the front matter. The front matter is everything between the ---s at the beginning of the file.

For new projects, use the following template:

```
---
layout: post
title:  "Put your title here"
date:   2021-04-31
excerpt: "This is a short description that should entice readers to want to read the full text."
project: true
tag:
- keyword
- other keyword
- etc...
feature: https://i.imgur.com/fU0XhVE.jpg
comments: true
---
```

1. From the main repo page click **_posts**

1. Click **Add a file**, and then click **Create a file**.

1. Enter the name of your project in the following format `year-month-day-project-title.md`, for example `2021-04-31-my-first-post.md`

   > Note that everything following the day will make up the post's URL, so keep it short.

1. Copy and paste the template from above into the file.

1. Customize the front matter. Additionally, you may
    - Delete `project: true` to create a new post.
    - Replace the link in `feature: https://i.imgur.com/fU0XhVE.jpg` with a link or path to the image you want to use.
    - Delete the `feature: https://i.imgur.com/fU0XhVE.jpg` line to create a project or post without an image.
    - Add or delete tags to be able to categorize your posts and projects on the [tags page](https://matcttu.github.io/tags/)

1. Write your post, and then click **Commit changes**. Note that it may take up to 10 minutes for your changes to rollout.

   For help with Markdown, see the [Markdown syntax page source](https://github.com/MATCTTU/matcttu.github.io/blob/master/_posts/2016-03-20-markdown-syntax.md) and [rendered page](https://matcttu.github.io/markdown-syntax/).

### Deleting posts and projects

1. From the main repo page click **_posts**

1. Click the file you want to delete.

1. Click the Trashcan icon.

1. Scroll all the way down, and then click **Commit changes**. Note that it may take up to 10 minutes for your changes to rollout.
