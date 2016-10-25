# DryFly-TheShortFilm.github.io

## How to

### Create a new post

To create a new post, follow the steps

* [Create post file](#create-post-file)
* [Add meta data](#add-meta-data)
* [Add an image](#add-an-image)

#### Create post file

Create a new file in the [_post folder](https://github.com/DryFly-TheShortFilm/DryFly-TheShortFilm.github.io/tree/master/_posts).

The file name must be something like *2016-07-11-summa-3d.md* where *2016-07-11* is the date and *summa-3d* will appear in the URL post.
Use only lower case characters, no special caracters, no accents, and only dashes as separators.
Note that the file extension must be **.md**.

#### Add meta data

The file must start with a [frontmatter](https://jekyllrb.com/docs/frontmatter/) that looks like

```
---
layout: post
title: Summa 3D
tags:
  - margarito
  - dryfly
  - 3D
  - Animación
  - premio
description: >
    Margarito arrasa allá donde va
---
```

It must contain:

1. `layout: post`
2. `title` with a verbatim title that will appear at the beginning of the post
3. `tags`: provided as a list
4. `description`: with a post description, it is recommended to put a pretty long description

The article is written in Markdown format that is really similat to plain text, and it is translated in HTML when you save hitting the **Commit changes** button at the bottom of the page.

#### Add an image

Every article must have a related image. Following the example above, the image will have the path *img/2016/07/summa-3d.jpg*.



## See also

* [Jekyll docs](https://jekyllrb.com/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
