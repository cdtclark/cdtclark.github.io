---
layout: post
title:  "1. Getting started"
date:   2021-11-08
excerpt: "Create a GitHub account, clone a repo, and create your first pull request"
tags:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

## Carousel

{% raw %}
{% capture images %}
	https://i.imgur.com/NIGYlVK.gif
	https://i.imgur.com/sqL26aO.gif
	https://i.imgur.com/Z3rzO7t.gif
    https://i.imgur.com/RV0kw0A.gif
    https://i.imgur.com/hsthdhY.gif
    https://i.imgur.com/g1hJqNC.gif
    https://i.imgur.com/jP06v9A.gif
    https://i.imgur.com/EmyzhGs.gif
{% endcapture %}
{% include gallery images=images caption="Test images" cols=1 %}
{% endraw %}

## Getting Started

1. [Create a GitHub account](https://github.com/join).

   > Note that the username you choose will be a part of your web address.

   Make sure you verify the confirmation email.
   
   ![Verify conformation email](https://i.imgur.com/NIGYlVK.gif)

1. Click **Fork** at the top of this page to make a copy of the `matcttu.github.io` repository.

   ![Click fork](https://i.imgur.com/sqL26aO.gif)

   After a few moments, all of the files will be copied into a repository you own.

1. Click **Settings**.

   ![Click settings](https://i.imgur.com/Z3rzO7t.gif)

1. Replace `matcttu` with your username, and then click **Rename**.

   ![Update the Repo name](https://i.imgur.com/RV0kw0A.gif)

   > Note that `username.githib.io` will be your site's URL or web address, but before you can visit your site, you need to update the config file.

1. Click `_config.yml` to open the file.

   ![Open _config.yml](https://i.imgur.com/hsthdhY.gif)

    This config file controls many aspects of the site including front page text, logo and background branding, and social icons, but you can ignore all of that for right now.

1. Click the Pencil icon to open the file for editing and then replace `MATCTTU` on line 11 with your username.

   ![Click the pencil icon](https://i.imgur.com/g1hJqNC.gif)

1. Scroll all the way down, then click **Commit changes**.

   ![Commit changes](https://i.imgur.com/jP06v9A.gif)

   > Note that commiting changes directly to the `master` branch and without descriptions is in fact a **BAD** practice. Avoid this in actual colaborative projects.

You can now view your live site at https://username.github.io, replacing `username` with your username, of course. If you don't see your site, go to **Settings** > **Pages** to verify GitHub Pages is publishing your site. You also may have to change the Source branch:

![Change source branch](https://i.imgur.com/EmyzhGs.gif)
