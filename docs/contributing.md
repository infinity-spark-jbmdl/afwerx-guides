---
layout: default
title: Contributing to the Guides
nav_order: 99
---
# Contributing to the Guides

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The goal of the AFWERX Guides project is for members of the community to contribute and improve
the guides.  The guides are open-source on [Github](www.github.com) at
[https://github.com/axelclark/afwerx_guides](https://github.com/axelclark/afwerx_guides).

You can contribute to the guides in three ways:

*  Report a bug (error)
*  Submit a suggested improvement
*  Develop a guide on a new topic

You need a [Github account](https://github.com/join) to contribute, but you can
do everything entirely through your web browser.

The guides are written using [Markdown](https://daringfireball.net/projects/markdown/).
Markdown is a way to style text on the web. If you are not familiar with
Markdown, check out this short article, [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
(3 min read).

## Report a Bug (Error)

Bugs (errors) are tracked as [GitHub issues](https://guides.github.com/features/issues/). First,
check the [existing issues](https://github.com/axelclark/afwerx_guides/issues)
to see if someone has already reported the problem. If they have and the issue is still open,
add a comment to the existing issue instead of opening a new one. If not, create a
[new issue](https://github.com/axelclark/afwerx_guides/issues/new). Explain the
problem and include additional details to help maintainers of the project fix it.

## Suggest an Edit

If you see a way to improve a guide or an error and have a suggestion for how to fix it, you can submit a
[pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
which will tell the maintainers of the project you have a suggested improvement.
Each page in the site has a link which will start the process of
[submitting a pull request from a fork](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request-from-a-fork)
to edit that page.

Once you submit the pull request, the maintainers will
review, edit (if needed), and then push the change to the website.

## Develop a New Guide

If you would like to develop a new guide, first submit your suggestion as a [new
issue](https://github.com/axelclark/afwerx_guides/issues/new). The contributors
will provide additional guidance.

Don't worry if you aren't familiar with
[Markdown](https://guides.github.com/features/mastering-markdown/), you can
write your guide using Google Docs and [convert it to Markdown](https://www.bettertechtips.com/how-to/convert-google-doc-to-markdown/). If
you view any of the [guide files](https://github.com/axelclark/afwerx_guides/tree/master/pages)
as "raw" you will see them written in Markdown.

Here are the steps to create a new guide:

1. Write the guide in Google Docs
1. [Convert to Markdown](https://www.bettertechtips.com/how-to/convert-google-doc-to-markdown/)
1. [Create a new file](https://help.github.com/en/github/managing-files-in-a-repository/creating-new-files) in the [pages folder](https://github.com/axelclark/afwerx_guides/tree/master/pages).
1. Paste in your Markdown text
1. Add Jekyll [front matter](https://jekyllrb.com/docs/front-matter/) to the top of
the guide for title and navigation. For example: 
    ```
    ---
    layout: default
    title: My New Guide
    nav_order: 4
    ---
    # My New Guide
    
    This is how to...
    ```
1. Submit change as a [pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
