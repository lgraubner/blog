---
title: Use of an identity function
date: 2021-03-30T12:00:00+02:00
description: ''
---

```javascript
const identity = (x) => x

const values = [null, 'Hello', false]

const filtered = values.filter(identity) // ['Hello']
```
