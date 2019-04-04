---
title: Testing the initial build
date: 2019-04-04T15:58:53.673Z
description: This is a description for the initial build blog post.
---
# So, here's some thoughts.

I wonder how good this WYSIWIG editor really could be if it only allows H1 and H2.

But oh well.

> Big time quote here from expert in the the WYSIWIG industry

I've been reading quite a bit and found that the following is important:

![Screenshot of Academic Ableism on Fulcrum](/img/screen-shot-2019-03-26-at-11.04.39-am.png "Here's a title bro.")

## Heading 2

Some more text for you to think about and consider. Let's try and copy pasta thingy.

## Revising fulcrum.org's Architecture

De-coupling the aboutware architecture of fulcrum.org from heliotrope will give us the flexibility to use different components, tools, and platforms for each piece of the fulcrum.org website. For example, a blog solution may not be useful as a knowledgebase solution or for a portfolio solution. 

### blog.fulcrum.org

Could either live separately from the rest of the aboutware, or, stuffs content in bulleit:./heliotrope/public/

### fulcrum.org

Portfolio site aimed at getting new clients interested in using fulcrum. /about, /services, /accessibility, and /preservation all fit under this. Could continue to be built with Jekyll using Jekyll admin, or something else.

### Heading
[docs.fulcrum.org](https://fulcrum.org)

Future site of documentation/knowledgebase for Fulcrum. This could be developer and user documentation. Live separately from the other components like the blog and the portfolio site.
