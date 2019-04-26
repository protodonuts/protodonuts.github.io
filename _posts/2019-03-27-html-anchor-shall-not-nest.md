---
title: HTML Anchor Element is not allowed to be in another anchor
---

```html
<a>haha<a>baba</a></a>
```

will be treated by browser as

```html
<a>haha</a><a>baba</a>
```

ref: https://stackoverflow.com/questions/18666915/why-are-nested-anchor-tags-illegal
