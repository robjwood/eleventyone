---
title: What is this?
date: 2019-06-14
---

There's not much here in the sample post page. Better get to work.

The common front-matter data for all of the files in the posts section are abstracted into a `posts.json` file so that we don't need to repeat that on every file. Handy.

It looks like this:

```js
{
  "layout" : "layouts/post.md",
  "tags" : "post",
  "templateEngineOverride": "njk,md"
}
```

