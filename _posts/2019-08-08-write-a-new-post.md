---
title: Writing a New Post
author: Cotes Chung
date: 2019-08-08 14:10:00 +0800
categories: [Blogging, Tutorial]
tags: [writing]
---

## Naming and Path

Create a new file named `YYYY-MM-DD-TITLE.EXTENSION` and put it in the `_posts/` of the root directory. Please note that the `EXTENSION` must be one of `md` and `markdown`.

## Front Matter

Basically, you need to fill the [Front Matter](https://jekyllrb.com/docs/front-matter/) as below at the top of the post:

```yaml
---
title: TITLE
date: YYYY-MM-DD HH:MM:SS +/-TTTT
categories: [TOP_CATEGORIE, SUB_CATEGORIE]
tags: [TAG]     # TAG names should always be lowercase
---
```
