# Front Matter

## title

- Type: `string`
- Default: `undefined`
- Required: `true`

The title for the page and content.

e.g.

```markdown
---
title: Hello World
---
```

## tags

- Type: `string|string[]`
- Default: `undefined`
- Required: `false`

The key to classifier pages and will also be displayed in the post:

<img src="../assets/tags.png" width="350px"/>
<img src="../assets/content-tags.png" width="350px"/>

e.g.

```markdown
---
tags: 
  - JavaScript
  - DOM
---
```

## date

- Type: `YYYY-MM-DD`
- Default: `undefined`
- Required: `false`

Date for the post. This will be used for permalink and displayed in the post:

<img src="../assets/date.png" width="350px"/>
<img src="../assets/content-date.png" width="350px"/>

e.g.
```markdown
---
date: 2016-10-20
---
```

## author

- Type: `string`
- Default: `undefined`
- Required: `false`

Author for the post. This will be displayed in the post:

<img src="../assets/author.png" width="350px"/>
<img src="../assets/content-author.png" width="350px"/>

e.g.

```markdown
---
author: ULIVZ
---
```

## location

- Type: `string`
- Default: `undefined`
- Required: `false`

Location for the post. This will be displayed in the post:

<img src="../assets/location.png" width="350px"/>
<img src="../assets/content-location.png" width="350px"/>

e.g.

```markdown
---
location: Hangzhou
---
```

## summary

- Type: `string`
- Default: `undefined`
- Required: `false`

Summary for the post. This will be displayed in the post:

![Summary](../assets/summary.png)

e.g.

```markdown
---
summary: Here's a quick post on what I found.
---
```
