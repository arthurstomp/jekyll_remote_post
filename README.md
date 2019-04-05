# Posting a remote post in 722 Blog

> This only works if you are a 722 member.

### Ola Galeris!

I've patched some JS into our Jekyll github page to allow us connect our Markdown posts with our community.

If any of you want to publish a blog post in our github page, you just need to do the following:

* Create a public repo with the markdown of your post;
* Create a new post file under our [github page repo](https://github.com/722-network/page)
``` markdown
---
layout: remote_post
title:  "First remote post"
date:   2019-03-25 18:16:41 -0300
author: "Arthur Rocha de Menezes"
author_link: "https://github.com/arthurstomp"
raw_source: "https://raw.githubusercontent.com/arthurstomp/jekyll_remote_post/master/README.md"
repo_source: "https://github.com/arthurstomp/jekyll_remote_post"
---
```
> If you still don't have access to this repo yet, feel free to bother [@arthurstomp](https://722-network.slack.com/team/UGSNLPZ88)
*  Make a merge request. And :boom: the post sent for mutual approval!

#SharingIsCaring

Peace out!
